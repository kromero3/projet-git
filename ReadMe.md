## Présentation du projet

Ce dépot Git est un projet de groupe consistant à utiliser les commandes git

## Groupe

Ce groupe est composé de :  Kénaël ROMERO   Arthur GUILLAUME    Louis JOUHANNET     Vincent GAILLARD

Test conflit

## Commandes de bases sur Git

- `git init`							   Initialise le dépôt
- `git add .`							   Ajoute/mets à jour le dépôt
- `git commit -m "message de commit"`	   Fait un message de commit
- `git push`							   Envoie les modifs au dépôt
- `git pull`							   Récupère les modifs du dépôt
- `git commit --amend -m "commit message"` Changer le titre du dernier commit
- `git diff`							   Affiche les modifs
- `git log`								   Affiche l'historique avec l'ID des commits
- `git checkout IDCommit`				   Reviens sur une versions plus ancienne en lecture seule
- `git checkout main`					   Retour à la version actuelle

### Branches

- `git log --graph`						   Historique
- `git checkout -b nomDeBranche`		   Créer une branche
- `git checkout branche`				   Se déplace dans une branche 
- `git log --all --graph`				   Historique
- `git merge branche`					   Rattache la branche au main
- `git -d`								   Supression de la branche

### Fonctions secondaires

- `git restore "fichier"`                  Supprimer les changements dans l'espace de travail
- `git restore -staged "fichier"`          à faire si le fichier est le fichier est en attente de commit
- `git clean -f`                           Force la suppression des fichiers non suivis

- `git stash`                              Met un sujet "sur le côté"
- `git stash pop `                         Décharge la pile

- `git log --grep`
- `git log -p -S`


Test