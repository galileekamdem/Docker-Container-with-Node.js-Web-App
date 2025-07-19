# Docker-Container-with-Node.js-Web-App
 
 Description du Projet

Ce projet démontre la création d'un conteneur Docker pour une application web Node.js simple utilisant Express. Il illustre les étapes complètes depuis l'initialisation du projet Node.js jusqu'au déploiement de l'application dans un conteneur Docker.

 Technologies Utilisées
Node.js (v18) - Environnement d'exécution JavaScript

Express (^4.16.1) - Framework web pour Node.js

Docker - Plateforme de conteneurisation

Alpine Linux - Distribution Linux légère pour le conteneur Docker


 Installation et Exécution
Prérequis
Docker installé sur votre machine

Node.js (optionnel pour développement local)

Étapes d'Installation
Cloner le dépôt

bash
git clone [URL_DU_REPO]
cd [NOM_DU_REPO]
Construire l'image Docker

bash
docker build -t todo-app .
Lancer le conteneur

bash
docker run -p 8080:8080 -d todo-app
Accéder à l'application
Ouvrez votre navigateur à l'adresse: http://localhost:8080
----------------------------------------------------------
 Compétences Développées
Configuration d'une application Node.js avec Express

Création d'images Docker optimisées

Gestion des dépendances dans un conteneur Docker

Construction et exécution de conteneurs Docker

Bonnes pratiques de conteneurisation (utilisation de .dockerignore)

 Points Forts du Projet
Optimisation: Utilisation d'Alpine Linux pour une image légère

Bonnes pratiques: Séparation claire des étapes de construction dans le Dockerfile

Portabilité: L'application peut s'exécuter de manière identique sur tout système supportant Docker

Automatisation: Les dépendances sont installées automatiquement lors de la construction
----------------------------------------------------------------

Ce projet a été réalisé dans le cadre de mon apprentissage continu des technologies de conteneurisation et du développement backend. Il démontre ma capacité à empaqueter une application dans un environnement isolé et portable, une compétence essentielle dans le développement moderne.
