### Dev web

ceci est une commande :
``` shell
    mkdir test
```

Ceci est du code:
``` javascript 
const test = 'Hello Xord';
``` 

La commande `git init` permet d'initialiser un depot GIT dans le local courant.

on utilise la commande :
```
git init
```

permet d'initaliser un depot GIT. Elle retourne:


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

Clé ssh:
Pour mettre notre notre cours sur Github


Le depot Git ou repository est le dossier qui contient les donnes que l'on souhaite versionner. On y trouve un dossier cache  `.git/`. 


recursive: la modification va se propager, si on save qlq chose dans le dossier Shayma utilisateur sa va s’appliquer a tout les sous dossier

La commande `git init` permet d'initialiser un depot GIT dans le local courant. Cela se traduit par la presence d'un dossier cache `.git/`a la racine du depot 

L'edition ou l'ajout de fichier dans ce repos sera detecte par Git, pour la visualiser dans le termina
On utilise la commande:
```
     git status
```

Avanr de sauvegarder les modifications, il faut ajouter les modifications que l'on souhaite sauvegarder avec la commande:
```
     git add <nom de fichier>
```

La sauvegarde s'effectue ensuite avec la commande:
```
git commit -m "message de commit
```

Sauvegarder le commit dans l'editeur de texte:
```
  :wq
```

chemin absolus, donc deplace toi a tel endroit. Chemin relatif commence tu chemin ou je suis 



envoyer sur l'origine:
```
git push
```


Pour nous configurer sur notre github:
```

git remote add origin https://github.com/Shasha-24/BTS-Cours.git
git branch -M main
git push -u origin main
```

Pour voir où est-ce que notre depot est :
```
git remote -v
```

supp l'url:
```
git remote -v
```

Ajouter notre adresse github:
```
ssh-keygen -t ed25519 -C shayma.merzougi@ecole-isistech.fr
faire entrer
ne pas mettre de mdp
aller voir dans notre dossier users la clé 
la mettre dans le site github
et faire ssh git@github.com
```

permet d'afficher la clé ssh:
```
$ cat id_ed25519.pub
```

etape pour save, toujours faire controle + s:
```
git add .
git commit
:x
git push
```

Pour avoir les notes d'un de mes camarades:
```
cd ..
git clone 'url du site'
code notes-sio/
```
