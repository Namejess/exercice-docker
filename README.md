# Exercice Docker

## Description
Ce projet contient les fichiers nécessaires pour lancer les conteneurs Docker de Redmine, MongoDB/Express et MySQL en utilisant Docker Compose.

## Prérequis
- Docker
- Docker Compose

## Installation
1. Clonez le projet sur votre machine locale.
2. Ouvrez un terminal dans le répertoire du projet.
3. Exécutez la commande `docker-compose up` pour lancer les conteneurs.

## Services
- Redmine: accessible à l'adresse `http://localhost:8080`
- Adminer: accessible à l'adresse `http://localhost:8081`
- MongoDB: accessible à l'adresse `mongodb://localhost:27017`
- Mongo Express: accessible à l'adresse `http://localhost:8082`

## Configuration
- Redmine:
  - Base de données MySQL: `db`
  - Mot de passe de la base de données MySQL: `example`
  - Clé secrète Redmine: `supersecretkey`
- MySQL:
  - Mot de passe root: `example`
  - Base de données Redmine: `redmine`
- MongoDB:
  - Nom d'utilisateur root: `root`
  - Mot de passe root: `example`
  - Base de données par défaut: `admin`
- Mongo Express:
  - Nom d'utilisateur MongoDB: `root`
 
## Screenshots 

![alt text](https://cdn.discordapp.com/attachments/830009390089764887/1166398484828668075/image.png?ex=654a583d&is=6537e33d&hm=088c36dbffa7936505de9d6be02c38918b2b92f124e6e1ac2d6213248fc724f2&)

![alt text](https://cdn.discordapp.com/attachments/830009390089764887/1166398573701763134/image.png?ex=654a5852&is=6537e352&hm=0212178a4734501a59286f11789cfb619eea8b25a281305bfc2cae75ae3de429&)

## Auteur
Github Copilot 😂
