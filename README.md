# Git-Commands
   Commandes pricincipales de git

+ `git init` Crée un dépôt Git vide ou réinitialise un dépôt existant.

 + `git add + NomFichier` Ajouter un ou plusieurs fichiers dans le repository crée.
     + tip = git add . ==> Ajoute tous les fichiers d'un dossiers dans le repository.

 + `git commit -m "NomCommit"` Enregistrer ses modifications par le biais d'un commit.

 + `git status` Affiche la liste des fichiers modifiés

 + `git log` Donne la liste de tous les commits effectués (du plus récent au plus vieux commit identifié chacun par un code SHA). 
     
 + `git checkout + SHADuCommit` Se positionner sur un commit précis.
     + tip = git checkout master ==> Revenir au commit le plus récent.

 + `git revert  + SHADuCommit` Crée un nouveau commit qui fait l'inverse du précédent.

 + `git commit --amend -m "NouveauNomCommit"` Permet de changer le nom du commit précédent (inutile si push déja effectué).

 + `git reset --hard` Permet d'annuler tous les changements fait aprés le dernier commit (à effectuer avant un nouveau commit).

 + `git clone + UrlRepositoryGitHub` Copier un repo GitHub dans un dossier (à faire initialement pour récupérer un projet puis préférer git pull).

 + `git push + NomRemote(origin étant le nom de remote par défaut) + NomBranche(master étant la branche principale par défaut)` Envoyer son projet dans le repository désigné sur GitHub.

 + `git pull + NomRemote(origin étant le nom de remote par défaut) + NomBranche(master étant la branche principale par défaut)` Récupérer un projet ou une partie de projet sur GitHub.

 + `git branch` Afficher la liste des différentes branches présentes sur un projet.

 + `git branch + NomBranche` Créer une nouvelle branche

 + `git branch -d NomBranche` Supprimer une branche en locale

 + `git push origin --delete NomBranche` Supprimer une branche d'un remote 


 + `git checkout + NomBranche` Accéder à une branche
     + tip= git checkout -b + NomBranche ==> Créer une nouvelle branche puis s'y positionner directement.

 + `git merge + NomBranche` Ajouter les modifications de la branche du nom désigné dans la commande.

 + `git blame + NomFichier` liste les modifications ligne par ligne d'un fichier

 + `git show + + SHADuCommit` Affiche détails d'un commit à partir de son code SHA

 + `git stash` Mettre de côté les modifications en cours sans avoir à faire un commit

 + `git stash pop` Revenir sur les modifications mises de côté








