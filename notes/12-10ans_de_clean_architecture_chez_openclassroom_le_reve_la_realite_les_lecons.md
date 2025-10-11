# 10 ans de Clean Architecture chez OpenClassrooms : le rêve, la réalité, les leçons

COMPTE-RENDU DE CONFÉRENCE
Titre de la conférence
10 ans de clean architecture chez Open Classroom, le rêve, la réalité, les leçons

Informations générales
- Date : 10 octobre 2025

- Heure : 15h56

- Format : Conférence présentielle lors d'une édition anniversaire de la FUP

Intervenants
- Olivier : Architecte chez Open Classroom, principal intervenant de la conférence

Résumé général
Cette conférence présente un retour d'expérience sur plus de 10 ans d'implémentation et d'évolution de la clean architecture chez Open Classroom. L'objectif est de partager comment cette architecture a été mise en place initialement, comment elle a évolué au fil du temps, les difficultés rencontrées, les simplifications apportées, et les leçons tirées de cette expérience. La présentation s'inscrit dans une réflexion sur l'adaptation pragmatique des principes théoriques aux besoins réels d'une application web basée sur PHP et Symfony.

Déroulé de l'intervention
Introduction et contexte historique
Olivier commence par préciser que cette conférence n'est pas un cours sur la clean architecture mais bien un retour d'expérience. Il raconte l'histoire du "Site du Zéro" (qui deviendra plus tard Open Classroom) entre 2011 et 2013, lorsque l'équipe travaillait sur une V3 qui montrait ses limites en termes de rigidité et de fragilité. Une refonte complète vers une V4 basée sur Symfony 2 a été entreprise, mais sa mise en production en janvier 2013 a été catastrophique, avec un site inaccessible pendant toute une journée et des semaines de corrections nécessaires par la suite. Cette V4 présentait les mêmes problèmes que la V3 qu'elle était censée résoudre : rigidité, fragilité, difficultés à tester, et couplage inapproprié dans le domaine métier. C'est dans ce contexte que la clean architecture a été introduite chez Open Classroom.

Principes de la clean architecture
Olivier présente brièvement les principes fondamentaux de la clean architecture, popularisée par Robert C. Martin (Uncle Bob) à partir de 2008 :

- Mettre le métier au centre de l'application

- Isoler le code métier du reste de l'application (framework, UI, base de données)

- Rendre chaque couche indépendante des autres

- Faire communiquer les couches par des abstractions

- Appliquer strictement les principes SOLID

- Favoriser la testabilité

- Révéler l'intention à travers l'organisation du code

Il explique le schéma classique de la clean architecture avec les entités au centre (logique métier), entourées des use cases (logique applicative), puis des couches externes (framework, infrastructure, données). Il souligne également l'ambiguïté potentielle entre les "entités" au sens clean architecture (porteuses de logique métier) et les "entités" au sens Doctrine/Symfony (représentations de données).

Première implémentation chez Open Classroom
Olivier détaille la première implémentation de la clean architecture chez Open Classroom en 2013, avec un schéma complexe comprenant de nombreuses couches :

- Un contrôleur qui reçoit une requête HTTP et envoie une réponse

- Un modèle de validation dans la couche framework

- Des builders pour générer les use case requests à partir des modèles validés

- Des use cases qui reçoivent des use case requests et produisent des use case responses

- Des gateways qui font l'interface entre les use cases et les sources de données

- Des assembleurs pour générer les responses et les view models

- Des interfaces pour chaque classe afin d'assurer l'indépendance des couches

Il présente des exemples de code pour illustrer cette implémentation, montrant comment le contrôleur, le use case et les assembleurs fonctionnent ensemble. Cette architecture était très stricte, avec des interfaces partout, respectant à 100% les principes SOLID, mais aussi très complexe, nécessitant la création de 20-30 classes pour chaque nouvelle route API.

Évolutions et simplifications
Au fil des années, l'équipe a identifié des points d'amélioration et a progressivement simplifié l'architecture :

1. Contrôleur unique : Création d'un "OpenController" basé sur les spécifications OpenAPI, qui standardise et automatise le traitement des requêtes et réponses, éliminant le besoin de créer un nouveau contrôleur pour chaque route.

2. Suppression des patterns systématiques : Constatant que les builders et assembleurs faisaient souvent du simple mapping d'attributs, l'équipe a créé un objet "hydrateur" pour automatiser ce processus et a tiré parti des named parameters de PHP pour simplifier la création des requests.

3. Réduction des interfaces : Après avoir constaté que 99% des use case requests n'étaient utilisées que par un seul use case, l'équipe a supprimé les interfaces pour les DTOs (Data Transfer Objects), tout en conservant les interfaces essentielles pour les autres composants.

Ces évolutions ont permis de simplifier considérablement l'architecture tout en préservant ses principes fondamentaux : isolation du métier, indépendance des couches, et testabilité.

Enseignements et bénéfices
Olivier partage plusieurs enseignements tirés de cette expérience :

1. Métier au centre : L'isolation du code métier est un "game changer" qui facilite l'évolution et les tests. Les temps d'exécution des tests sont passés de 30 minutes à quelques secondes.

2. Pragmatisme vs dogmatisme : L'approche initiale était très dogmatique, mais avec l'expérience, l'équipe a appris à être plus pragmatique, en adaptant l'architecture aux besoins réels de l'application.

3. Comprendre pourquoi : Il est crucial que tous les membres de l'équipe comprennent pourquoi l'architecture est conçue ainsi, surtout lors de l'onboarding de nouveaux développeurs.

4. Cohésion : "Tout ce qui change pour les mêmes raisons devrait être au même endroit." L'équipe a gagné en cohésion en centralisant certaines sources de vérité, comme les spécifications OpenAPI.

Le bilan est globalement très positif : l'objectif initial de ne plus avoir à faire de refonte complète a été atteint, l'application a pu évoluer continuellement pendant 12 ans sans refonte majeure, et les performances des tests et de la CI se sont considérablement améliorées.

Perspectives futures
Pour l'avenir, Olivier évoque plusieurs pistes d'évolution :

- Recentrer la logique métier dans les entités, qui a eu tendance à glisser vers les use cases

- Explorer une structure par composants, où chaque composant métier aurait sa propre architecture clean mais serait organisé de manière plus cohésive

- Continuer à adapter l'architecture au contexte et aux besoins évolutifs de l'entreprise

Questions / Discussions
La session de questions a été très brève. Un participant a simplement mentionné qu'il détestait habituellement la clean architecture, probablement en référence à sa complexité initiale nécessitant la création de nombreux fichiers pour des fonctionnalités simples.

Points à retenir
- La clean architecture a permis à Open Classroom de passer d'une application fragile et rigide à une application robuste et évolutive

- L'isolation du code métier est fondamentale pour la testabilité et l'évolutivité

- Une approche pragmatique est préférable à une application dogmatique des principes théoriques

- L'architecture doit s'adapter au contexte, au business et à l'évolution des technologies

- La compréhension des principes par toute l'équipe est essentielle pour maintenir la cohérence

- La cohésion (regrouper ce qui change pour les mêmes raisons) est un principe important

- L'architecture n'est jamais figée et doit continuer à évoluer

Conclusion
Cette conférence démontre comment une architecture technique bien pensée peut transformer radicalement la stabilité et l'évolutivité d'une application. Le parcours d'Open Classroom avec la clean architecture illustre parfaitement l'équilibre à trouver entre rigueur architecturale et pragmatisme opérationnel. Après plus de 10 ans, le bilan est très positif : l'application a pu évoluer sans refonte majeure, les tests sont devenus beaucoup plus efficaces, et l'équipe a gagné en productivité. Ce retour d'expérience souligne l'importance d'adapter les principes théoriques aux besoins réels et de faire évoluer l'architecture en fonction du contexte, tout en conservant ses fondamentaux.