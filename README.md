**Nom :** Roche Gabriel

**Groupe :** A2

**Année :** 2023

**IUT Le Havre - Cours GIT**

### Compte-rendu TP1 Introduction GIT

Dans ce TP on apprend à travailler avec git.

Initialiser un dépôt :
```bash
git init
```

Ajouter un fichier au commit :
```bash
git add <file>
```

Supprimer un fichier au commit :
```bash
git remove <file>
```

Effectuer un commit :
```bash
git commit -m <message> 
```

Publier la dernière version du dépôt local sur github :
```bash
git push
```

Télécharger la dernière version du dépôt distant :
```bash
git pull
```

Afficher l'historique des commits :
```bash
git log
```

Afficher le status du dépôt :
```bash
git status
```

Clôner un dépôt distant :
```bash
git clone <adresse>
```

Afficher la branche courante :
```bash
git branch
```

Changer de branche :
```bash
git branch <nom de la branche>
```

Créer une branche :
```bash
git checkout -b <nom de la branche> 
```

#### Pour configurer git

Afficher la liste des paramètres :
```bash
git config --list
```

Afficher la valeur d'un paramètre :
```bash
git config <paramètre>
```

Changer la valeur d'un paramètre :
```bash
git config --global <paramètre> <valeur>
```

#### Publication

Afficher les dépôts distants reliés au dépôt local :
```bash
git remote -v
```

Lier un dépôt local à un dépôt distant :
```bash
git remote add origin <adresse ssh>
```

Lier de manière permanente le dépôt :
```bash
git push -u origin master
```