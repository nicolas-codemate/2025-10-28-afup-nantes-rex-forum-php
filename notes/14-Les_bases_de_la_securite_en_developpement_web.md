RAPPORT DE CONFÉRENCE
Titre de la conférence
Les bases de la sécurité en développement web
Informations générales
- Date : 10 octobre 2025 à 14h20
- Format : Conférence en présentiel
- Auteur du rapport : Nicolas Demay
Intervenants
- Amaury Bouchard - Directeur technique chez Omunity
Résumé général
Cette conférence visait à présenter les fondamentaux de la sécurité en développement web. Amaury Bouchard a abordé les
principales vulnérabilités de sécurité couramment rencontrées dans les applications web, en expliquant leur
fonctionnement et en proposant des solutions concrètes pour s'en protéger. La présentation avait pour objectif de
sensibiliser les développeurs aux enjeux de cybersécurité et de leur fournir des bonnes pratiques à mettre en œuvre dans
leurs projets.
Déroulement de la conférence
Présentation d'Amaury Bouchard
Amaury Bouchard s'est présenté comme Directeur technique chez Omunity. Il a mentionné avoir été coordinateur à l'UF de
Paris dans les années 2010 et être impliqué dans l'Open Source. Il anime également un blog intitulé "Geek & Directeur
Technique", gère le compte PHP Zen sur les réseaux sociaux, et le site "PHP Way of Life".
L'importance de la sécurité
Amaury Bouchard a commencé par souligner l'importance de la sécurité informatique avec des chiffres marquants :
- Le coût de la cybercriminalité en France est estimé à environ 100 milliards d'euros en 2024
- Deux tiers des entreprises françaises ont subi des attaques en 2024
- 15% des petites et moyennes entreprises ont connu un incident cyber au cours de l'année précédente
- 60% des entreprises ayant subi une attaque réussie ferment leurs portes dans les 18 mois suivants
Il a ensuite présenté les principaux vecteurs d'attaque :
1. Le phishing (courriels frauduleux)
2. L'exploitation de vulnérabilités (sujet principal de la conférence)
3. Le déni de service (empêcher un serveur de répondre correctement)
Sources d'information sur la sécurité
© 2025 Geremy
Demay Nicolas Demay
• on 10/10/2025 Page 2 / 4
L'intervenant a recommandé plusieurs ressources pour approfondir le sujet :
- Le projet OWASP et son Top 10 des vulnérabilités (dernière mise à jour en 2021)
- Le projet Secure Readers pour des informations sur les en-têtes HTTP
- La fondation Mozilla et son service HTTP Observatory
- L'ANSSI (Agence Nationale de la Sécurité des Systèmes d'Information)
- Les différents CERT (centres de veille et d'alerte aux attaques)
Injections SQL
Amaury Bouchard a expliqué le principe de l'injection SQL : envoyer des données qui modifient le comportement des
requêtes SQL exécutées sur le serveur.
Il a illustré ce concept avec l'exemple d'une page de désinscription à une newsletter :
- Un formulaire simple demande l'adresse e-mail
- Le code backend exécute une requête SQL pour supprimer l'abonnement
- Si un utilisateur malveillant entre ' OR TRUE à la place d'une adresse e-mail, la requête devient DELETE FROM subscription
WHERE email = '' OR TRUE, ce qui efface tous les abonnements
Solutions proposées :
1. Échapper les chaînes intégrées dans la requête (avec mysql_real_escape_string ou PDO::quote)
2. Utiliser des requêtes préparées
3. Utiliser un constructeur de requêtes (ORM)
L'intervenant a insisté sur le principe fondamental : "Ne jamais faire confiance aux données entrantes."
Cross-Site Scripting (XSS)
Amaury Bouchard a défini le XSS comme l'injection de code JavaScript dans une page web, qui s'exécutera lors de la visite
d'autres personnes sur le site. Les objectifs peuvent être :
- Récupérer des informations d'authentification
- Faire exécuter du code sur les ordinateurs des visiteurs (minage de cryptomonnaie, participation à un botnet)
Il a illustré cette vulnérabilité avec l'exemple d'un système de commentaires :
- Un attaquant peut insérer une balise <script> qui exécutera du code JavaScript
- Ce code peut envoyer les cookies des utilisateurs vers un serveur externe
- Des alternatives existent comme l'utilisation d'une balise <img> avec un attribut onerror
Solutions proposées :
1. Ne jamais faire confiance aux données entrantes
2. Contrôler les données intégrées dans les pages
3. Supprimer les balises HTML avec la fonction strip_tags (sans autoriser aucune balise)
4. Échapper les données lors de l'affichage (encoder les caractères spéciaux en entités HTML)
5. Nettoyer le code HTML avec des bibliothèques comme HTML Purifier ou Symfony HTML Sanitizer
Bonus :
- Utiliser l'en-tête HTTP Content Security Policy pour interdire l'exécution de JavaScript inline
- Marquer les cookies comme HTTP-only pour les rendre inaccessibles en JavaScript
Server-Side Request Forgery (SSRF)
L'intervenant a expliqué que le SSRF consiste à pousser un système à se connecter à des URL non prévues pour :
- Vérifier leur existence
- Récupérer leur contenu
- Faire exécuter des actions
Il a illustré ce concept avec l'exemple d'un site qui propose de résumer des pages web via IA :
- Si le code utilise file_get_contents, un attaquant pourrait accéder à des fichiers locaux en entrant file:///etc/passwd
- Il pourrait également scanner les ports du réseau interne avec des URL comme http://192.168.1.1:8000
- Il pourrait même exécuter des API internes non sécurisées avec des URL comme
http://192.168.1.1/internalapi/deleteuser/27
Solution proposée :
- Vérifier rigoureusement les données entrantes (protocole, nom de machine, adresse IP)
Cross-Site Request Forgery (CSRF)
Amaury Bouchard a expliqué que le CSRF consiste à pousser un utilisateur à effectuer des actions sans le vouloir sur un
système où il est authentifié.
Exemple :
- Un administrateur est connecté à une console d'administration
- Il reçoit un e-mail de phishing avec un lien qui semble légitime
- En cliquant sur ce lien, il est redirigé vers une URL qui effectue une action sensible (comme la suppression d'un utilisateur)
- L'action est exécutée car l'utilisateur est déjà authentifié
Solutions proposées :
1. Vérifier le référent HTTP (s'assurer que la requête provient du même domaine)
2. N'accepter que les requêtes POST pour les actions sensibles
3. Créer des cookies de session avec le paramètre SameSite défini sur Lax ou Strict
L'intervenant a souligné que la combinaison de ces trois méthodes est très efficace et plus simple à mettre en œuvre que les
jetons CSRF traditionnels.
Configuration du serveur HTTP
Amaury Bouchard a conclu avec des recommandations rapides sur la configuration du serveur HTTP :
- Configurer HTTPS (avec Let's Encrypt pour des certificats gratuits)
- Rediriger les requêtes HTTP vers HTTPS
- Utiliser les en-têtes de sécurité HTTP :
- X-Content-Type-Options pour empêcher le navigateur de deviner le type MIME
- X-Frame-Options pour empêcher l'inclusion du site dans une iframe
- Content-Security-Policy pour contrôler les sources de contenu
- Empêcher l'accès aux fichiers sensibles (.env, .git)
- Désactiver l'affichage des fichiers dans les répertoires
- Masquer les informations de version du serveur
Questions / Discussions
Le modérateur a indiqué qu'il n'y avait pas de temps pour les questions mais a invité l'audience à venir voir Amaury
Bouchard pendant la pause pour lui poser directement des questions.
Points clés à retenir
- Ne jamais faire confiance aux données entrantes (principe fondamental répété tout au long de la conférence)
- La cybersécurité représente un enjeu économique majeur (60% des entreprises victimes d'attaques réussies ferment dans
les 18 mois)
- Pour les injections SQL : utiliser des requêtes préparées ou des ORM
- Pour le XSS : échapper systématiquement les données lors de l'affichage ou utiliser des sanitizers HTML
- Pour le SSRF : valider rigoureusement les URL et les protocoles
- Pour le CSRF : combiner la vérification du référent, les requêtes POST et les cookies SameSite
- Configurer correctement les en-têtes de sécurité HTTP
- Utiliser HTTPS systématiquement
Conclusion
Cette conférence a fourni une introduction complète aux fondamentaux de la sécurité web, en se concentrant sur les
vulnérabilités les plus courantes et leurs solutions. Amaury Bouchard a souligné l'importance de ne jamais faire confiance
aux données entrantes et d'adopter une approche proactive de la sécurité. Les exemples concrets et les solutions pratiques
présentés constituent une base solide pour les développeurs souhaitant sécuriser leurs applications web. La cybersécurité
apparaît comme un enjeu crucial non seulement techniquement mais aussi économiquement pour les entreprises de
toutes tailles.