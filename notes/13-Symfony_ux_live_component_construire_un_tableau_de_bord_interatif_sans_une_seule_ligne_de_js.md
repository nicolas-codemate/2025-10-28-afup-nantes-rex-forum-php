RÉSUMÉ DE LA CONFÉRENCE
Titre de la Conférence
Symfony UX Live Component : Construire un tableau de bord interactif sans une seule ligne de JS
Informations Générales
- Date : 10 octobre 2025 à 14h48
- Format : Conférence en présentiel
- Auteur du résumé : Nicolas Demay
Intervenants
- Félix Emouno : Développeur PHP et Symfony, fondateur de la société Goodeven, collaborateur chez Packslash et
contributeur open source à diverses bibliothèques dont Symfony UX
Aperçu Général
Cette conférence démontre comment créer un tableau de bord interactif avec Symfony UX Live Component sans écrire une
seule ligne de JavaScript. À travers un cas pratique divisé en cinq itérations, Félix Emouno montre comment implémenter
progressivement des fonctionnalités interactives (recherche, graphiques, tri, filtres et rafraîchissement automatique) en
utilisant uniquement PHP et Twig, tout en maintenant une expérience utilisateur dynamique généralement associée à
JavaScript.
Déroulement de la Conférence
Introduction
Félix Emouno commence par se présenter et introduire le sujet de sa conférence : créer un tableau de bord interactif sans
JavaScript en utilisant Symfony UX Live Component. Il mentionne qu'il va raconter une histoire vraie, légèrement adaptée
pour la présentation, qui se déroulera en cinq actes. Avant de commencer, il sonde l'audience pour savoir qui utilise déjà
Twig Component et Live Component.
Contexte du Projet
L'histoire commence par un email d'un Product Owner demandant un tableau de bord simple pour l'équipe commerciale,
affichant les ventes du mois. La première version est rapidement développée en Twig pur, mais est suivie de demandes
d'améliorations pour ajouter des fonctionnalités interactives comme la recherche, les graphiques, le tri, les filtres et le
rafraîchissement automatique.
Itération 1 : Implémentation de la Recherche
Approche Traditionnelle vs Live Component
Félix explique que l'approche traditionnelle pour implémenter une recherche interactive nécessiterait :
- Créer une API
- Gérer le debounce pendant la saisie
- Gérer l'affichage et les erreurs
- Environ une journée de développement
© 2025 Geremy
Demay Nicolas Demay
• on 10/10/2025 Page 2 / 4
Solution avec Live Component
La solution présentée utilise :
- Un composant avec deux propriétés : page pour la pagination et query avec l'attribut LiveProp
- Un template Twig avec un input utilisant data-model="query" pour la liaison avec la classe PHP
- Le résultat : une recherche interactive sans JavaScript en seulement 30 minutes
Félix fait une démonstration en direct montrant comment la recherche filtre instantanément les résultats sans
rechargement de page.
Itération 2 : Ajout d'un Graphique Interactif
Approche Traditionnelle vs Live Component
L'approche traditionnelle nécessiterait :
- Un nouveau point d'API
- Écouter les changements de filtres
- Mettre à jour les données et le graphique
- Environ une journée supplémentaire de développement
Solution avec Live Component
La solution présentée utilise :
- Un composant enfant pour le graphique avec une propriété query
- L'attribut update_from_parent pour synchroniser le graphique avec la recherche
- L'intégration de Chart.js via Symfony UX
- Le résultat : un graphique qui se met à jour automatiquement avec la recherche en 30 minutes
Félix explique le concept de composants imbriqués et l'importance de l'option update_from_parent pour forcer la mise à
jour du composant enfant lorsqu'une propriété parente change.
Itération 3 : Implémentation du Tri
Approche Traditionnelle vs Live Component
L'approche traditionnelle nécessiterait :
- Un nouveau point d'API
- Implémenter la fonction de tri côté client
- Gérer l'interface visuelle pour les flèches de tri
- Gérer un état pour la colonne et la direction de tri
Solution avec Live Component
La solution présentée utilise :
- Deux nouvelles propriétés : sortBy et sortDir
- Une méthode pour gérer le tri des données
- L'attribut data-action pour déclencher une action au clic
- Les attributs data-live-action-param pour passer des paramètres à l'action
- Le résultat : un tri interactif en 35 minutes
Félix explique le schéma de fonctionnement : un événement déclenche une action, l'état du composant est modifié, ce qui
génère un nouveau rendu et une mise à jour de l'affichage.
Itération 4 : Ajout de Filtres
© 2025 Geremy
Demay Nicolas Demay
• on 10/10/2025 Page 3 / 4
Approche Traditionnelle vs Live Component
L'approche traditionnelle nécessiterait :
- Gérer les selects
- Synchroniser les états
- Gérer les URLs pour partager les filtres
- Complexité accrue en JavaScript
Solution avec Live Component
La solution présentée utilise :
- Deux nouvelles propriétés : status et period avec l'option url_true
- Mise à jour automatique de l'URL avec les paramètres de filtres
- Le résultat : des filtres interactifs et partageables en 30 minutes
Félix démontre comment les filtres fonctionnent et comment l'URL se met à jour automatiquement, facilitant le partage
d'une vue filtrée.
Itération 5 : Rafraîchissement Automatique
Approche Traditionnelle vs Live Component
L'approche traditionnelle nécessiterait :
- Gérer un setInterval
- Faire du polling avec l'API
- Optimiser pour éviter le spam de rafraîchissement
- Gérer les conflits entre actions simultanées
- Gérer la concurrence
Solution avec Live Component
La solution présentée utilise :
- L'attribut data-poll sur la div racine du template
- Un délai configuré (10 secondes pour la démo)
- L'option $render pour forcer le rendu du composant
- Le résultat : un rafraîchissement automatique en 5 minutes
Félix démontre cela en générant des ventes aléatoires qui apparaissent automatiquement dans le tableau de bord sans
intervention de l'utilisateur.
Résumé et Cas d'Utilisation
Félix présente un résumé des cinq itérations :
- Zéro ligne de JavaScript écrite
- Un tableau de bord entièrement interactif
- Pas de maux de tête ni de débogage JavaScript
Il précise les cas d'utilisation adaptés aux Live Components :
- Projets existants en Twig pur nécessitant de l'interactivité
- Équipes principalement back-end avec peu d'expertise JavaScript
- Tableaux de bord, panneaux d'administration, CRUD
Et les cas moins adaptés :
© 2025 Geremy
Demay Nicolas Demay
• on 10/10/2025 Page 4 / 4
- Applications avec beaucoup d'animations
- Applications ultra temps réel (comme les chats)
- Projets utilisant déjà des frameworks front-end
Conclusion
Félix conclut en citant Marc Moser : "La technologie la plus profonde est celle qui disparaît", soulignant que Live Component
fait disparaître JavaScript pour les développeurs back-end tout en maintenant l'interactivité. Il dédie sa présentation à Ryan,
qui a grandement inspiré la communauté PHP et Symfony, et mentionne que le code de démonstration est disponible sur
GitHub.
Questions / Discussions
Une question a été posée sur le débogage des Live Components en cas de problèmes :
Question : Comment peut-on déboguer les Live Components quand les choses ne fonctionnent pas ?
Réponse de Félix Emouno : Comme il n'y a pas de JavaScript à proprement parler, nous pouvons utiliser le Web Profiler de
Symfony pour le débogage. Les Live Components fonctionnent principalement avec des requêtes Ajax et peuvent être
considérés comme des pseudo-contrôleurs. Le Web Profiler permet de voir les requêtes effectuées, les paramètres envoyés
et d'identifier les problèmes potentiels.
Points Clés à Retenir
- Les Live Components permettent de créer des interfaces interactives sans écrire de JavaScript, en utilisant uniquement
PHP et Twig
- L'attribut LiveProp rend une propriété PHP réactive au niveau de la vue
- L'option update_from_parent permet de synchroniser les composants enfants avec leurs parents
- Les actions peuvent être déclenchées depuis le template avec data-action et des paramètres peuvent être passés avec
data-live-action-param
- L'option url_true permet de mettre à jour l'URL avec les valeurs des propriétés pour un partage facile
- Le polling natif avec data-poll permet un rafraîchissement automatique sans WebSocket
- Les Live Components sont particulièrement adaptés aux tableaux de bord, panneaux d'administration et CRUD
- Le débogage se fait via le Web Profiler de Symfony comme avec les contrôleurs classiques
Conclusion
Cette conférence démontre la puissance de Symfony UX Live Component pour créer des interfaces interactives sans
JavaScript, offrant une alternative précieuse pour les équipes back-end. En présentant un cas concret de tableau de bord
avec cinq itérations progressives, Félix Emouno a illustré comment des fonctionnalités généralement complexes à
implémenter en JavaScript peuvent être réalisées simplement et rapidement. Cette approche permet non seulement de
gagner du temps de développement mais aussi aux développeurs de rester dans un environnement PHP familier tout en
offrant une expérience utilisateur moderne et interactive.