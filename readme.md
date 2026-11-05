# TP1 – assisant de revision

## Présentation

on a  créer un fichier **README.md** afin de documenter le projet Python développé lors du TP1. Le programme **main.py** constitue un assistant de révision qui a été amélioré progressivement grâce à Git et GitHub.

Le README permet à une autre personne de comprendre le projet, ses différentes versions, son fonctionnement et les commandes Git utilisées durant les travaux pratiques.

## Évolution du programme

### V1 : Programme initial
La première version du programme affiche un message de bienvenue destiné à l'utilisateur. Cette version a été créée localement sur le PC puis enregistrée avec un premier commit Git.

### V2 : Ajout du prénom utilisateur
Le programme demande désormais le prénom de l'utilisateur et affiche un message personnalisé. Cette version a été enregistrée par un nouveau commit puis publiée sur GitHub à l'aide de la commande `git push`.

### V3 : Ajout de la matière à réviser
Une nouvelle fonctionnalité a été créée directement sur GitHub. Le programme demande la matière que l'utilisateur souhaite réviser et l'affiche à l'écran. Cette modification a ensuite été récupérée sur le PC grâce à la commande `git pull`.

### V4 : Ajout de la durée de révision
Le programme demande enfin le nombre de minutes prévues pour la révision. Il affiche alors un objectif complet contenant la matière choisie et la durée de travail. Cette version a été créée localement puis envoyée vers GitHub avec un nouveau `git push`.

## Comment exécuter le programme

### Avec Visual Studio Code

1. Ouvrir le dossier **TP_Git_Python** dans Visual Studio Code.
2. Sélectionner le fichier **main.py**.
3. Cliquer sur **Run Python File** (▶) en haut à droite.
4. Le terminal intégré s'ouvre automatiquement.
5. Saisir les informations demandées :
   - prénom ;
   - matière à réviser ;
   - durée de révision en minutes.
6. Valider chaque réponse avec la touche Entrée.

### Outils nécessaires

- Python
- Visual Studio Code
- Git
- GitHub

## Commandes Git utilisées

### git init
Initialise un dépôt Git dans le dossier du projet.

### git add
Place les modifications dans la zone de préparation avant leur enregistrement.

### git commit
Crée une nouvelle version du projet avec un message descriptif.

### git push
Envoie les commits locaux vers le dépôt GitHub distant.

### git pull
Récupère les nouvelles modifications présentes sur GitHub et les intègre dans le projet local.

## Conclusion

Ce projet a permis d'apprendre à utiliser Git et GitHub pour suivre l'évolution d'un programme Python. Les commandes de versionnement ont facilité l'enregistrement, le partage et la synchronisation des différentes versions du fichier main.py.
