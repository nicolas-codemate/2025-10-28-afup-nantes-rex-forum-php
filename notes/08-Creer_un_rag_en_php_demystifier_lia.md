# Créer un rag en php : démystifier l'ia

Llm n'ont accès qu'aux données publiques
Rag = génération augmentée par la récupération
C'est un pattern

Ajout au contexte du llm, une base documentaire indexé
Base de données vectorielle recommandé

Chunking, découpage du texte, par séparateur ou saut de ligne, ou sémantique (changement de sens = découpage) 

On peut pas tout faire en php, découpage 'notamment 
Processus php qui pilote cette tâche 
- api externe, openai, mistral.. 
- local avec ollama 

On reçoit un tableau de vecteur 


Il faut stocker dans bdd vectorielle (pgvector) 
Support doctrine 

Exemple utilisation 
Chatbot règlement rh 

Existe des solutions clé en main, Rag as service 

