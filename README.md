# Grp-3
# Système d'Authentification Sécurisé en PHP (Architecture MVC)

## Description

Ce projet est une application web d’authentification développée en PHP, basée partiellement sur le modèle *MVC* (Model - View - Controller). Il permet :
- L’inscription et la connexion sécurisées des utilisateurs
- La validation stricte des mots de passe
- La gestion des sessions et la protection contre les failles courantes

## Fonctionnalités

- Création de compte avec :
  - Nom d’utilisateur
  - Email
  - Mot de passe complexe
- Connexion via email ou nom d’utilisateur
- Vérification d’unicité du compte
- Hashage sécurisé des mots de passe (password_hash)
- Sécurité contre les injections SQL

## Architecture

Le projet suit une architecture inspirée du modèle *MVC* :
## Installation

1. Cloner ce dépôt ou le télécharger
2. Importer le fichier database.sql dans phpMyAdmin
3. Modifier Database.php avec vos identifiants MySQL
4. Lancer avec un serveur local (XAMPP ou Laragon)
5. Accéder à localhost/auth-system/signup.php

## Dépendances

- PHP ≥ 7.4
- MySQL
- Navigateur web moderne

## Auteur

Réalisé dans le cadre d’un devoir universitaire (Sécurité Web).

---


## Présentation

Ce projet est une application d'authentification simple développée en PHP, en respectant l'architecture MVC. Il permet aux utilisateurs de créer un compte, se connecter, et se déconnecter de manière sécurisée.



Exo10/ │ ├── controllers/ │   └── Users.php               # Contrôleur pour la gestion des utilisateurs │ ├── helpers/ │   └── session_helper.php      # Fonctions pour la gestion des sessions │ ├── libraries/ │   └── Database.php            # Classe pour la connexion à la base de données │ ├── models/ │   └── User.php                # Modèle représentant l'utilisateur │ ├── Photos/                     # Dossier pour les images utilisées dans le site │ ├── footer.php                  # Pied de page inclus dans les vues ├── header.php                  # En-tête inclus dans les vues ├── index.php                   # Page d'accueil ├── login.php                   # Formulaire de connexion ├── signup.php                  # Formulaire d'inscription │ ├── style.css                   # Fichier de style principal ├── style1.css                  # Fichier de style secondaire ├── style 2.css                 # Fichier de style alternatif └── README.md                   # Documentation du projet
