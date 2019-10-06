# Environnements logiciels pour la programmation avancée de terminaux mobiles

## Polytech Nice Sophia-Antipolis


### Frigolthy
Equipe de travail:
* Ghada Khedira
* Rihab Zaafouri

### Introduction
ce projet est réaliser dans le cadre d'un apprentissage academique du module des terminaux mobiles de la majeur IAM. Il vise à integrer le concept de l'embarqué avec les applications mobiles à travers la communication entre les capteurs , les differents composants embarqués ainsi que les services web integrés.

### Contexte de réalisation
Les nouvelles technologies sont devenues primordiales dans notre vie quotidienne, alors pour nous permettre de garder une vie saine et de préparer des repas équilibrés en quelques minutes nous avons décidé de créer une application mobile intitulée "Frigolthy" (Frigo-healthy). 
Cette application nous proposera des recettes avec un coût minimal, avec des produits qui existent réellement dans notre réfrigérateur et elle veillera à ce qu'on ne dépasse pas la date d'expiration de nos aliments.

### Scénario
*  Tout d'abord pour accéder à Frigolthy l'utilisateur peut s'identifier avec son empreinte digitale.
*  L'utilisateur scanne les dates de fabrication et les dates d'expiration des produits achetés avec la caméra du téléphone. Par suite, les dates scannées vont être traitées à l'aide d'un algorithme de reconnaissance d'écriture, afin d'alerter l'utilisateur en cas de dépassement de ces dates.
*  Notre application vous proposera des recettes faciles et des repas healthy rapides en fonction des ingrédients disponibles dans votre frigo.
* Dans le cas d'absence d'un ingrédient nécessaire pour la préparation d'une recette choisie, Frigolthy vous proposera aussi le magasin le plus proche de votre emplacement par le biais du GPS.

# Choix Technologique 

## Développement Mobile
Dans cette partie , on va developper une application mobile avec Kotlin , un language crée par Google facilitant le developpement mobile avec Android. Ce dernier est  plus riche comparant avec Java , flexible et concis.c'est un language de programmation orienté objet et fonctionnel , avec un typage statique qui permet de compiler pour la machine virtuelle Java et JavaScript . 

Cette technologie offre plein d'avantages , nous allons les decrire selon les aspects suivant:

* UX: Il offre de trés bonne performance et scalable , de sorte qu'il est un code natif , il nous assure la portabilité du code et la varieté de la faisabilité tout en gardant des meilleurs fonctionnalités 
* Developpement: Notre outils de developpement sera Android Studio , IntelliJ ou même Visual Code , et ce  afin de guarantir une compilation plus rapide grâce à la possibilité de recharge automatique lors du changement du code et de façon instantannée . 
* Design: Integration de plein d'outils d'animation et faire recourt aux composants matériels deja existants
* Maintenance: Deboggage de l'application en cas de besoin. Maintenabilité de l'application de sorte qu'elle est supporté par un language developpé par Google. Anciennes versions sont supportés



### Les capteurs
* Empreinte digitale
* Appareil photo
* GPS
### Environnement de développement
* Android Studio
### Langage de programmation
* Kotlin
