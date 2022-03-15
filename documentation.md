# Documentation technique

## Rappel du cahier des charges

### Introduction
Dans le cadre du 2ème travail de semestre, j'ai décidé d'effectuer un projet qui me sera très utile pour le travail de diplôme. L'idée serait de faire une application web qui affiche des données d'entrainement avec chart.js

#### But du projet

#### Contraintes techniques
Pour ce projet, nous devions utiliser un framework de notre choix. L'application réaliser doit également être compatible mobile.

### Analyse

#### Technologies 
* Python
* Markdown
* Github (versionning, task manager)
* Ordinateur de type PC, 2 écrans
* Visual Studio Code
* Mkdocs (Documentation)
* Python Flask
* Chart.js

##### Python Flask
Flask est un micro-framework python facile et simple d'utilisation qui permet de faire des applications web évolutives. Flask dépend de la boite à outils WSGI de [Werkzeug](https://werkzeug.palletsprojects.com/en/2.0.x/) et du moteur de templates [Jinja](https://jinja.palletsprojects.com/en/3.0.x/).

###### Installation
Pour installer Flask il suffit d'entrer la commande : 
```
pip install Flask
```

##### Micro framework
Un micro framework est un framework qui tente de fournir uniquement les composants absoluments nécessaires à un développeur pour la création d'une application. Par exemple dans le cas d'une application Web, un micro framework peut être spécifiquement conçu pour la construction d'API pour un autre service/application.

Le terme *micro* dans le micro framework signifie que Flask vise à garder le code de base simple mais extensible. Flask ne prendra pas beaucoup de décisions, par exemple quelle base de données utiliser. Les décisions qu'il prend, telles que le moteur de templates à utiliser, sont faciles à modifier. Tout le reste est libre, de sorte que Flask puisse répondre à tous nos besoins et à tous ce que vous ne voulez pas en même temps.

En définissant uniquement le moteur de templates et un système de routes, Flask laisse le choix de personnaliser (en ajoutant des packages) pour la gestion des formulaires par exemple.

#### Environnement de développement

#### Modèle de données

## Analyse fonctionnelle

### Interface

### Fonctionnalités

## Analyse organique
### Architecture
#### Arborescence de fichier
```
+-- docs
|	+-- documentation.md
|	+-- logbook.md
+-- mkdocs.yml
```

## Tests

## Conclusion