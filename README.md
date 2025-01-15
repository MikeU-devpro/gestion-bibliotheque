# gestion-bibliotheque

## Description

Ce projet est une application de gestion de bibliothèque. Elle a pour but de permettre la gestion des membres, des livres ainsi que des emprunts dans une bibliotheque de façon automatique.

## Fonctionnalités

- **Gestion des membres** : Ajouter, modifier et supprimer des membres.
- **Gestion des livres** : Ajouter, modifier et supprimer des livres.
- **Emprunts** : Enregistrer les emprunts de livres par les membres, y compris les dates d'emprunt et de retour prévues.
- **Système de Recherche** : Rechercher un livre par titre, auteur ou catégorie.
- **Calcul des retards et des pénalités** : Calculer le retard à partir de la dateRetourPrevue et appliquer une pénalité le cas échéant.

## Technologies Utilisées

- **Base de données** : PostgreSQL
- **Langage de programmation** : SQL pour les requêtes, Java pour le reste.
- **Environnement de développement** : Intellij IDEA

## Installation

1. Clonez le dépôt :
   ```bash
   git clone https://github.com/MikeU-devpro/gestion-bibliotheque.git

2. Accédez au répertoire du projet :
   ```bash
   cd gestion-emprunts

3. Créez la base de données :
   ```bash
   CREATE DATABASE bibliotheque;

4. Exécutez le script de création des tables et d'insertion des données :
   ```bash
   \i chemin/vers/le/fichier_de_creation.sql
   \i chemin/vers/le/fichier_d_insertion.sql

