# Documentation avec Git

Git est un système de contrôle de versions qui permet de suivre les modifications d’un projet et de collaborer.

## Démarrer

```bash
git init                 # Initialiser un dépôt
git clone <url>          # Cloner un dépôt distant
git status               # Consulter l’état des fichiers
```

## Enregistrer des modifications

```bash
git add <fichier>        # Préparer un fichier
git add .                # Préparer toutes les modifications des fichiers
git commit -m "Message"  # Créer un commit
git log --oneline        # Consulter l’historique
```

## Branches et dépôt distant

```bash
git branch                 # Lister les branches
git checkout -b <branche>  # creation d'une branche
git switch -c <branche>    # Créer et rejoindre une branche
git switch <branche>       # Changer de branche
git pull                   # Récupérer les changements
git push                   # Envoyer les commits

```
```bash
git remote add origin    #<URL-du-dépôt>
```

Vérifiez les changements avec `git status` avant de les enregistrer. Utilisez un message de commit court et descriptif.

pour les bonnes pratique, on va integrer la notion revue de code. pour cela, on va créer une brache , faire des modifications, les envoyer sur le dépôt distant, puis créer une pull resquest pour demander une revued de code.
