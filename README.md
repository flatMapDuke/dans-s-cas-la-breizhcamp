Dans s'cas là.
==============
Auteurs
-----------
Ludwine Probst @nivdul
Mathieu Chataigner @mchataigner
Jonathan Winandy @ahoy_jon
Jean Helou @jeanhelou

Pré-requis
------------
Vous avez besoin :
* D'une connexion internet 
* De java 6+ (vous pouvez le vérifier en lançant java -version)
* Un éditeur de texte (nous recommandons sublime-text)

Lancer le Hands-on
------------

Vous pouvez lancer le hands-on en tapant 
* ```./handson``` sous linux/mac
* ```handson.bat``` sous windows 

Ces scripts lancent SBT (scala build tool) en arrière plan préconfiguré avec des commandes pour jouer le hands-on. La commande principale est : 

    go

Cette commande lance le premier test et surveille les fichiers, chaque fois que vous modifiez un fichier elle rejoue le test en cours, une fois qu'un test est passé, la commande passe au test suivant.

Il y a d'autres commandes qui permettent de lancer chaque chapitre indépendament:
* ```partie1-1``` - découverte des bases du langage, variables mutables & immutables, classes, case classe et ```for expresssions```
* ```partie1-2``` - api des listes, maps, sets, option, fonctions de plus haut niveau, extracteurs et pattern matching
* ```partie2``` - comprendre le fonctionnement de map et de flatMap dans différents contextes, initiation simple à la variance
* ```partie3``` - construire une implementation de List immutable, construire un stream (liste infinie évaluée à la demande)
* ```partie4``` - (bonus) Introduction aux Type Clas
* ```partie5``` - (bonus) Revisiter map et flatmap dans un cas plus complexe
* ```partie6``` - (bonus) Un exemple d'event sourcing

Compléter l'exercice prends plusieurs heures, n'hésitez pas a demander de l'aide sur [la mailing list du PSUG](https://groups.google.com/forum/?fromgroups#!forum/paris-scala-user-group)
