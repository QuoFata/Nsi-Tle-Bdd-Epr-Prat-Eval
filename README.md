# Nsi-Tle-Bdd-Epr-Prat-Eval1
NSI Terminale - Base de données : épreuve pratique d'évaluation

Le but est de mettre les élèves en situation pratique d'évaluation.

Une base de données relationnelle sert de support à cette épreuve.
La page d'accueil en fait une description.
Le sujet est : "les erbres remarquables des Côtes d'Armor".
Source : https://datarmor.cotesdarmor.fr/data-presentation-ux/#/cg22/datasets/i2x3pbj8/views/grid

Il leur est demandé d'écrire des requêtes en SQL qui répondent à des questions.
Ils soumettent leurs requêtes et voient s'afficher le résultat de leur requête.
Si ce résultat leur convient ils passent à une autre question, et ce jusqu'à épuisement de la liste.
Sinon ils peuvent réssayer une autre requête, autant de fois qu'ils veulent, dans la limite du temps imparti.
Chaque essai est journalisé.

Chaque élève s'identifie par un code que lui fournit l'enseignant.
Aucune identité réelle n'est conservée dans l'application.

Ressources requises :
> * Un SGBD en ligne, personnel ou chez un hébergeur ;
> * un serveur web, personnel ou chez un hébergeur, accessible via FTP

Mise en service ;
> * créer la base de données avec un utilisateur en limitant les droits de ce dernier
> * importer les tables et les datas dans la base de données
> * téléverser sur le serveur web les fichiers html, css, php... de l'application
> * paramétrer l'accès à la base de données dans le fichier 'soumRequete.php'
