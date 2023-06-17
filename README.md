# Mcommerce_App
Ce projet Mcommerce_App a été réalisé en binôme (LABAALLI Mahjouba & ALAOUI Fatimaezzahra) dans le cadre d'un projet académique. 
Mcommerce_App est une application de commerce électronique basée sur une architecture de microservices. Elle est conçue pour gérer les fonctionnalités essentielles d'une boutique en ligne, notamment la gestion des commandes, des paiements et des produits.

## Architecture
L'application Mcommerce_App est composée des éléments suivants :

- Commande : Microservice responsable de la gestion des commandes, de la validation et du suivi des commandes des clients.
- Paiement : Microservice chargé de gérer les transactions de paiement, d'intégrer les passerelles de paiement et de confirmer les paiements effectués par les clients.
- Produit : Microservice en charge de la gestion des produits, y compris la création, la mise à jour, la suppression et la recherche de produits dans la base de données MongoDB.
- Frontend (Clientui) : Interface utilisateur développée en React, offrant une expérience utilisateur interactive et conviviale pour parcourir les produits, passer des commandes et effectuer des paiements.

## Technologies utilisées
- Node.js : Plateforme JavaScript côté serveur pour la construction des microservices.
- Express.js : Framework Web utilisé pour la création des API RESTful des microservices.
- MongoDB : Base de données NoSQL utilisée pour stocker les données des produits, des commandes et des paiements.
- React : Bibliothèque JavaScript pour la construction de l'interface utilisateur frontend.
- HTML/CSS : Langages de base pour la structuration et la mise en forme des pages web.

## Installation
1. Clonez ce dépôt GitHub sur votre machine locale.
2. Accédez au répertoire du projet : *cd Mcommerce_App*.
3. Installez les dépendances nécessaires : *npm install*.
4. Configurez les variables d'environnement, telles que les informations de connexion à la base de données.
5. Démarrez chaque microservice en exécutant la commande *npm run server*  dans leur répertoire respectif.
6. Accédez au répertoire du frontend et exécutez *npm run start* pour lancer l'interface utilisateur.

## Remarque 
Il faut dans un premier temps se connecter à la base de données puis lancer le microservice Produit.

## Licence
Ce projet est distribué sous la licence MIT.