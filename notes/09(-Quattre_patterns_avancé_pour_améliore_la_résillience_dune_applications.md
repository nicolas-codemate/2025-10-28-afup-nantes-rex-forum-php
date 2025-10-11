# Quatre patterns avancé pour améliorer la résilience d'une application 

Random jitter
Introduire de l'aléatoire pour lisser les query

Exponential backoff
Attendre de plus en plus longtemps

Constant work
Attendre d'avoir un nombre fix de traitement à faire, quitte à combler avec des demandes fictives  => pas de variabilité, robuste

Cell based architecture
Réduire le rayon d'explosion d'une application
Découper, isoler
Cellule, sous élément indépendant, isolé

Shuffle sharding

