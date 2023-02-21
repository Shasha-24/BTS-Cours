## Dev web

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
récuperer de l'externe:
```
git pull
```

## HTML

Permet de structurer les pages web

page web basic, dans index.html :
```
html 5 + tab = 
```

c’est une balise qui est constituer d’une partit ouvrante et fermante

afficher du texte:
```html
<p> "le texte" </p>
```

Un élément HTML est composé d'une balise d'ouverture et une balise de fermeture 

certain elements HTML n'ont pas de balise fermante:
```html 
<hr>
```

Chaque element HTML peut avoir un ou plusieur attributs, ajout de photo:
```
<p id="test"> ceci est un paragraphe </p>

<img src="images/images.jpg" alt="image not found" title="titre de l'image>

```
 permet de faire une bande au dessus de notre texte:

```
<header></header>
```

L'element <html> est l'element racine des pages HTML. 

L'element head:

Il contient des proprietes essentielles pour les page web.

Chacune de ces proprietes est renseigner avec des éléments enfants 


toujours mettre:
```
</body>
</html>
```

dans une grosse boite donc <html> il y a 2 petite boites, 
head et body, head sont les elements non visible mais necessaire, body lui sont les elements visible 




Conception d'une page web

Pour concevoir vos pages, vous devez réfléchir  en termes de " conteneur". Un conteneur, comme son nom l'indique, inclut un contenu de type très varié.

Da,s ces conteneurs, vous pourrez placer du texte, des images, des formulaires, des liens, des tableaux.... Mais vous pourrez aussi avoir des conteneurs plus " petits " comme pour mettre uen evidence un ou plusieur mots, ou oiur définir une cellule de tableau .

L'element <div> est un des conteneurs les plus anciens du HTML. Il permet de créer une division structurelle dans la page.
Dans ces divisions, nous pouvons placer d'importe quel contenu et même d'autres conteneurs comme d'autres division <div>, des paragrapges, des listes.... Ces divisions permettaient d'effectuer des mises en page à l'aide de conteneurs " neutre ", c'est a dire sans element definit 

### l'element header

L'element " header " permert d'insérer une zine d"affichage pour les pieds de page. Nous retrouvons la même sémantique que pour les entêtes.
Ces pieds de page peuvent être définis pour la page

### L'element nav

L'element " nav ", comme son nom le laisse supposer, est décider a l'affichage d'une barre de navigation avec des liens hypertextes. Mais attention, ne vous sentez pas obliger de n'avoir qu'une seule zone de navigation par page, à partir du momment ou chacun d'entre eux est bien identifier. 

creer un tableau:
```
<pre> </pre>
```

permet d'ouvrir dans une nouvelle fenetre:
```
`target="_blank"`
```

## CSS

Le role du CSS:

On peut appliquer du style a certains elements a l'aide l'attribut class. En CSS on cible les elements dont la classe est test de la maniere suivante:
```CSS 
.test {
     test -transform: uppercase;
}
```

On peut aussi en CSS appliquer du style de maniere specifique grace a l'attribut html id:
```CSS
#test {
     /*ceci est un commentaire */
}
```


#### Structure et regles du CSS

```
selecteur {
     props: valeur
}
```
Les selecteurs:
- ne doivent pas commencr par un chiffre
- ne peuventpas contenur d'espace, de caractères speciaux, de caracteres avecc accents
- peuvent contenir des '-' et des '_'
-sont sensibles a la casse 

Les expressions regulieres
lien: https://developer.mozilla.org/fr/docs/Glossary/Regular_expression

#### Les selecteurs de pseudo-classes

changer la couleur:
```
a:visited{
     color: rgb(32,92,11);
     background-color: aqua;
}
```

autre exemple:
```
a:hover{
     color: rgb(171,129,95)
     background-color: green;
}
```
asset: imagine, document etc..
