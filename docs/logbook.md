# Logbook

## 21 Décembre 2021
Création du cahier des charges, du dépôt GIT ainsi que le Trello pour le projet.
## 11 Janvier 2022
Révision du cahier des charges, je choisis d'utiliser react pour le projet même si je n'ai pas énormement d'expérience avec. Je commence a créer quelques composants pour mes premières vues.
## 18 Janvier 2022
Je vois qu'avec npm je peux directement intégrer [Chart.Js](https://www.npmjs.com/package/chart.js) dans mon projet avec la commande : 
```
npm i chart.js
```
Je continue mes composants pour créer une vue représentant le tableau de bord principal
## 25 Janvier 2022
J'ai regardé quelques sample d'utilisation de Chart.JS et essaye de l'implémenter dans mon projet pour afficher des graphiques.

## 01 Février 2022
J'ai pu ajouter un composant sur mon tableau de bord avec un graphique (Chart.JS), problème avec l'échelles sur le graphiques (Impossible de réduire l'échelles à .5). J'avance sur les autres vues (Login/Register). J'ai également eu le temps de créer ma base de données pour pouvoir stocker les données utilisateurs.

## 08 Février 2022
En travaillant sur mon travail de semestre, je me suis rendu compte que Python Flask serait vraiment très utile pour mon travail de diplôme et je pense de plus en plus à l'utiliser. Je pense donc changer de Framework et recommencer avec Flask, sachant que j'ai passé une grande partie du temps à me documenter sur Vue je peux rattraper assez vite en utilisant Flask. Je créer une page d'accueil avec Flask et je commence directement le Login/Register.

## 22 Février 2022
J'avance sur mon application de base avec Python Flask. J'ai regardé quelques tutos sur youtube pour en apprendre un peu plus sur le fonctionnement de Python Flask. J'ajoute une base de données pour enregistrer quelques infos sur les utilisateurs. Je découvre la librairies python SQL Alchemy.

## 1 Mars 2022 
Absent (Covid-19)

## 8 Mars 2022
J'ai pu avancé sur mon application Flask, j'ai maintenant un Login/Register fonctionnel et une page "dashboard" qui me permet de modifier les infos de l'utilisateurs. J'utilise SQL Alchemy pour relier la base de données, SQLite pour le moment car la connexion était plus simple. Il faut que je regarde comment faire la connexion pour une base MySQL (Pas la même que pour SQLite).

## 15 Mars 2022
J'ai réussi à faire la transition sur MySQL. J'ai du changé l'URI dans la config SQLAlchemy. J'ai également du installer un module en plus **pymysql** qui me permet d'établir la connexion (je le rajoute dans le requirements.txt)
 
Commande : 
```
pip install pymysql
```

Je découvre pipreqs qui permets de générer le fichier requirements.txt avec tous les packages et leurs versions.