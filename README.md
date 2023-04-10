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