# TP n°1 : Création d’un projet open-source

Dans ce tutoriel nous allons créer notre premier projet open-source. Dans le but de comprendre :

* comment publier du code source sur internet en respectant les bonnes pratiques de développement. 
* comment documenter son projet.
* comment faire du code de qualité
* comment faire un suivi de son projet.

Notre projet :

Dans ce premier projet nous allons créer un petit programme qui permet d’effectuer des opérations en utilisant Python. Notre programme pourra être appelée depuis le terminal prendra comme paramètre add sub div mul suivi de deux et fera l’addition la multiplication et la division. 

## Partie 0
Apprentissage des bases en Python, effectuer la partie 1 et 2 qui seront nécessaire à la compréhension de cette formation
https://openclassrooms.com/fr/courses/235344-apprenez-a-programmer-en-python

## Partie 1 : Création d’un projet sur Github.

Nous allons créer un projet sur le site Github que nous appellerons “calculette-python”. La création d’un nouveau repository se passe ici : https://github.com/new


Nous initialiserons notre projet avec un fichier Readme.
Avant de valider nous allons faire un point sur ce qu’est une licence logicielle. Nous en discuterons ensemble lorsque tout le monde aura réalisé la partie 1.


Enfin nous allons récupérer localement notre projet git pour celà depuis un terminal nous allons effectuer la commande suivante :

git clone https://github.com/votrepseudo/calculette-python.git


Par exemple mon pseudo git étant ludovic-bouguerra
La commande est donc : git clone https://github.com/ludovic-bouguerra/calculette-python.git


Nous allons avoir maintenant un dossier nommé calculette-python observez le contenu.


## Partie 2 : Création de notre projet calculatrice

Nous allons créer un projet Python. Il suffit pour cela de créer un nouveau document texte  dans l’éditeur visual studio, dans le dossier calculette-python nous l’appelerons calculette.py

Pour tester notre programme il faudra depuis une console effectuer la commande suivante dans le dossier calculette-python effectuer la commande “python calculette.py”

Quels sont les outils dont nous allons avoir besoin : 
Comment effectuer un affichage dans un terminal en python

Comment récupérer les paramètres saisis par les utilisateurs dans le terminal

Comment effectuer des conditions en python et comparer des chaînes de caractères.

**Premier objectif** : Afficher “Calculatrice” lorsque l’utilisateur lance l’application.

Après chaque objectif rempli nous allons devoir effectuer un commit c’est à dire publier nos modifications, il s’agira de publier les modifications dans notre code source. 

Pour celà nous effectuerons l’opération suivante :
Recherchez sur internet comment faire un commit en utilisant l’utilitaire git et ce que celà représente.
Effectuer votre premier commit en envoyant le contenu modifié de votre fichier calculatrice.py


**Second objectif** :  Ajouter la fonctionnalité d’addition
Le programme doit lors que l’utilisateur effectue la commande suivante :

```
python calculatrice.js add 2 3 
```

Le programme doit afficher le résultat suivant :

```
Calculatrice 
5
```

Comment vérifier en utilisant git quelle est la différence entre mes nouvelles modifications et mon fichier initial ?
Effectuer le commit en y mettant un message approprié

**Troisième objectif** : Ajouter la fonctionnalité de soustraction

Même processus que précédent mais avec la notion de soustraction.

**Quatrième objectif** : Ajouter la fonctionnalité de multiplication

Même processus que précédent mais avec la notion de multiplication.

**Cinquième objectif** : Ajouter la fonctionnalité de division
Même processus que précédent mais avec la notion de division.


## Partie 3 : Documentation de notre projet

Nous allons à présent documenter notre projet, pour cela nous allons le faire de deux manières différentes, la première voie sera via **l’utilisation du Wiki de Github**. La seconde sera de compléter **le fichier Readme**
.
Quel est le format des fichiers Readme.md sous github ?
Essayez de faire apparaitre dans le fichier Readme.md des :
Tableaux 
Un titre principal
Un titre secondaire
Faites la modification d’abord directement sur Github et une autre en modifiant en réalisant un commit. 
Que constatez-vous lorsque vous souhaitez effectuer le commit après une modification sur Github.

## Partie 5 : Bonus

* Comprendre ce qu’est une branche
* Comprendre ce qu’est une pull request
* Comprendre ce qu’est l’intégration continue


