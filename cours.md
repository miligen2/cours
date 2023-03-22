# Dev WEB
## TEST 
Ceci est une command : 

``` bash
mkdir test 
```

Ceci est du code :

``` javascript
const test = 'Hello World';
``` 

Sur Visual studio se diriger sur le terminal : 

``` 
Angel@????? MINGW64 ~/Desktop/BTS SIO/Dev/devweb
```
il nous informe notre nom et le dossier dans le quel on développe.

Commande :

``` bash
 pwd 
 /c/Users/Angel/Desktop/BTS SIO/Dev/devweb
``` 
Cette commande nous informe dans quel dossier nous sommes.


## Cours 

git = le logiciel et le format

github = un des sites de partage

### Les commandes Git: 

Permet d'initialiser un dépot Git.
```
git init
```

 Elle retourne : 

``` 
Initialized empty Git repository in C:/Users/Angel/Desktop/BTS SIO/Dev/devweb/.git/
```
Creer une branche du nom de main :
```
git branch -M main
```

Pour verifier l'état de votre dépot Git utiliser la commande :

``` 
git status
```
Le dépot Git ou est le dossier qui contient les donnees que l'on souhaite versionner. On y 

Permet d'ajouter les modificatinos que l'on souhaite sauvegarder : 
```
git add .
```
Permet de sauvegarder la derniere version elle est utilisé après la commande `git add` : 

```
git commit -m "message de commit"
```
Permet d'obtenir l'adresse https ou ssh pour faire notre dépot : 

```
git remote add origin (https or ssh)
```
permet de se mettre dans la branche nomé main : 

```
git branch -M main
```

permet de déposer notre commit sur git : 
```
git push -u origin main 
```
si une fois dedans cela ne fonctionne pas faire : 
```
git reset --hard origin/main
```
---
### Definition Git

`git commit` : Permet d'enrengistrer dans notre dépot 

`git add` : Permet d'ajouter un fichier pour qu'il soit pret à être enrengristrer  

`git init` : permet d'initialiser un dépot git local dans le répertoire courant. Cela se traduit par la presence d'un dossier cacher `.git/` à la racine du dépot. 

---

### Les commandes Bash 

Cette commande nous informe dans quel dossier nous sommes : 

``` bash
pwd
```

Pour ce déplacer dans les documents :

``` bash 
cd 
```
Pour supprimer un fichier ou un document : 
```bash
rm 
```
Pour lister ce qui se trouve dans le document :
```bash
ls -la 
``` 

Creation d'une clé SSH : 
```
ssh-keygen -t ed25519 -C "your_email@example.com"
```
Puis suivre les indications. 

On peut deployer son site sur github, versel 








