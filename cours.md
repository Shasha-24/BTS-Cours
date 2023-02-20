### Dev web

ceci est une commande :
``` shell
    mkdir test
```

Ceci est du code:
``` javascript 
const test = 'Hello Xord';
``` 

La commande `git init` permet d'initialiser un depot GIT

La commande :
```
git init
```
permet d'initaliser un depot GIT. Elle retourne:
```


Pour verifier l'etat de votre depot Git utiliser la commande
:
```
git status
```

changement enregistrer de un/plusieurs fichier, ouvre un editeur de texte (permet de commenter) :
```
commit 
```

ajoute le prochain changement de commit :
```
git add
```

liste les changements:
```
git change
```

ajoute tout les changement de commit :
```
git add . 
```

sorir de l'editeur de texte:
```
:q
```
Pour qu'il soit connecter à notre github:
ajouter un nom :
```
git config --global user.name "Shayma MERZOUGUI"
```

ajouter un email:
```
git config --global user.email shayma.merzougui@ecole-isitech.fr
```
créer un commit avec comme message "first commit"
```
git commit -m "first commit"
```

aller voir l'historique:
```
git log
```



Le depot Git ou repository est le dossier qui contient les donnes que l'on souhaite versionner. On y trouve un dossier cache  `.git/`. 