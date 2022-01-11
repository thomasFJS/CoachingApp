# Cahier des charges
## Sujet
Créer une application WEB mobile permettant d'afficher des données d'entrainement avec des graphiques 

## But du projet
Le but du projet est de créer une plateforme WEB qui permet de gérer plusieurs données d'entrainements et avoir un aperçu sur la progression. Les données suivantes sont prises en comptes :

* Pulsation cardiaque (Repos/Actif/Après effort)
* Le type d'exercice effectué
* Date et durée de l'entrainement
* Nombre de total de calories brulées 
* Nombre de calories active
(Optionnel)
* Les données relatives au sommeil 
    * Pulsation cardiaque
    * Cycles de sommeil
    * Interruption
    * Hypnogramme
 

## Utilisation
La plateforme Web permet de s'enregistrer soit en tant que praticant, soit en tant que coach.

**En tant que praticant** :
On a accès à nos données d'entrainements et au différents programme que le coach à publié pour nous. Un système de notification est mis en place pour avertir lorsqu'un nouveau programme/bilan est disponible

**En tant que coach**: 
On peut accéder aux données de tous nos praticants avec les courbes de progression. On peut importer les différents programmes des praticants directement depuis l'application. Un système de facturation est mis en place pour les praticants. 


## Spécifications
* Les données d'entrainements sont récupérées depuis une base de données
* Les graphiques liés aux stats sont effectués avec la librairie javascript Chart.js
* Le tableau de bord permettant d'afficher et de gérer toutes les données est réalisé avec ReactJS
* Les programmes d'entrainements et de nutritions doivent respecter le format proposé (Lors de l'upload une vérification est effectuée)


## Environnement
Technologies utilisées :

* HTML5
* CSS3 
* PHP
* Javascript
* SQL
* RactJS
* [Chart.js](https://www.chartjs.org/)


Système d'exploitation :

* Développement sur Windows

Versionning / Documentation :

* GitHub
* MarkDown (Mkdocs)

## Livrable
* Fichier zip contenant le projet + bdd
* Documentation technique et journal de bord au format PDF