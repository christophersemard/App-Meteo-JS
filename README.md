<h1 align="center">🌦️ App Météo JS</h1>

<p align="center">Application météo statique avec recherche de ville et géolocalisation du navigateur.</p>

<p align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" alt="HTML5" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" alt="CSS3" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=111827" alt="JavaScript" />
  <img src="https://img.shields.io/badge/OpenWeatherMap-API-EF6C00?style=flat-square" alt="OpenWeatherMap API" />
</p>

## À propos

Cette application frontend interroge OpenWeatherMap pour afficher la météo actuelle et les prévisions d'une ville. Elle propose aussi une recherche basée sur la géolocalisation du navigateur.

## Fonctionnalités

- recherche par nom de ville ;
- utilisation de la position du navigateur ;
- météo actuelle et prévisions ;
- icônes et arrière-plans adaptés aux conditions ;
- interface responsive sans framework.

## Lancer localement

Remplacer d'abord le placeholder de clé OpenWeatherMap dans app.js par une clé personnelle, puis ouvrir index.html ou servir le dossier avec un serveur statique :

    python -m http.server 8000

Ouvrir ensuite http://localhost:8000.

La clé historique a été retirée du dépôt public. Elle ne doit jamais être committée dans un fichier JavaScript frontend.

## Contexte

Projet de formation consacré aux appels fetch, à la géolocalisation et à la manipulation du DOM.

## Auteur

[Christopher Semard](https://github.com/christophersemard)
