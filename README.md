# FormationDTA-Git

![Logo Git](http://www.mimastech.com/wp-content/uploads/2016/10/git.png "Logo Git")

Ce dépôt est créé dans le cadre de la formation Git par Diginamic.

## Historique

Git est un logiciel libre créé par [Linus Torvalds](https://fr.wikipedia.org/wiki/Linus_Torvalds), auteur du noyau Linux,  en 2005 et distribué selon les termes de la licence publique générale GNU version 2. En 2016, il s’agit du logiciel de gestion de versions le plus populaire qui est utilisé par plus de douze millions de personnes.

Source [Wikipedia](https://fr.wikipedia.org/wiki/Git)

## Quelques commandes utiles

```bash
git init                  # Initialise un dépôt Git

git pull                  # Récupère les commits distants

git add <file>            # Ajoute le fichier à l'index
git add .                 # Ajoute tous les fichiers modifiés à l'index

git commit -m <message>   # Crée un commit avec le titre <message>

git push                  # Envoie les commits locaux vers le serveur distant

git fetch                 # Récupère l'historique des commits

git checkout <branch>     # Change de branche active pour <branch>

git checkout -b <branch>  # Crée une branche <branch> et la définit comme branche active

git branch                # Donne la branche courante

git merge <branch>        # Fusionne la branche actuelle avec la branche <branch> en récupérant les commits divergeant depuis le commit actuel
```
