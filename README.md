# 🎬 Conception d'une base de données pour la réservation de séance au cinéma 🎥

⏰ Durée : 4 heures 30 minutes

Tout support est autorisé (internet, projets précédents...)

🤖 L'utilisation d'IA est autorisée pour t'aider à résoudre des bugs ou t'orienter dans tes recherches. Le copier-coller
de code n'est pas autorisé.

👨‍🎨 Il n'est pas nécessaire de faire de design ou plusieurs vues pour ce projet.

🧘 Pas d'inquiétude si tu ne termines pas tout le projet. L'objectif est de montrer ta compréhension de la conception et l'utilisation des outils proposés par Laravel.

## ℹ️ Introduction

L'objectif de ce projet est de mettre en pratique tes compétences en conception et modélisation de bases de
données pour créer le schéma d'une application de réservation de places de cinéma. 

En utilisant Laravel et ses outils,
tu devras créer les migrations, les relations entre les modèles ainsi que les Factory et Seeders afin de remplir ta base
de données.

## Prérequis 

Effectue un fork du repository avec ton compte GitHub pour réaliser le projet.

## 🎯 Besoin client

L'application doit permettre aux utilisateurs de rechercher des séances de cinéma disponibles dans une ville pour une
date donnée, de choisir un film et de réserver des places pour ces séances.

### Détails du besoin

#### Gestion des films :

Les détails sur les films, tels que le titre, le genre, la durée et
sa [classification](https://fr.wikipedia.org/wiki/Commission_de_classification_des_%C5%93uvres_cin%C3%A9matographiques)
doivent être disponibles pour les utilisateurs.
Chaque film peut être diffusé dans plusieurs séances dans différents cinémas.

#### Gestion des séances :

Chaque séance doit être associée à un film, une salle, une date et une heure.

#### Gestion des Salles :

Les salles ont une capacité maximale de places.

#### Gestion des Réservations :

Les utilisateurs doivent pouvoir réserver une ou plusieurs places pour une séance donnée.

⚠️ La liste des besoins n'est pas exhaustive en termes de tables et de champs à créer.

### 🔎 Requêtes métier

1. Récupérer la liste des films diffusés dans un cinéma pour une date.
2. Récupérer la liste des séances pour un film dans un cinéma pour une date.
3. Trouver le nombre de places restantes pour une séance donnée.
4. Trouver le ou les films que personne n'a encore réservé. 🚨
5. Trouver les films les plus populaires ce mois-ci. 🚨

🚨Tu ne peux pas utiliser directement les ID pour récupérer les données.

## Tâches à réaliser

**Analyse des Besoins** : Utilise les besoins et les informations du sujet pour identifier les entités et détermine les relations entre ces entités.

**Conception de la Base de Données** : À partir de ton analyse des besoins, défini les tables, leurs attributs et les relations entre elles.

**Implémentation** : Utilise Laravel pour créer des migrations basées sur le schéma de la base de données que
tu as conçu. Assure-toi que les migrations créent les tables nécessaires avec les contraintes d'intégrité
appropriées.

**Interroger la BDD** : Ecrit des requêtes en utilisant les modèles Eloquent pour récupérer des données.

## Critères d'évaluation

- Versioning : Le projet contient un historique git montrant une progression dans la réalisation du projet.
- Conception de la base de données : Les entités principales sont identifiées et les relations entre elles
  sont correctement définies.
- Implémentation : Les migrations s'exécutent sans erreurs et créent les tables nécessaires avec
  les contraintes d'intégrité appropriées.
- Relations entre les tables : Les relations entre les tables sont bien définies dans les models.
- Remplissage de la base de données : Les Factories et les Seeders sont utilisés et remplissent la BDD.
- Best practices : Le code est écrit en respectant
  les [conventions de Laravel](https://github.com/alexeymezenin/laravel-best-practices).

## 📦 Livrables

- Diagramme illustrant les entités, les attributs et les relations en fonction des besoins exprimés.
- Projet Laravel contenant les migrations, les relations entre les modèles, les Factories et les Seeders pour remplir la
  base de données.
- Requêtes pour récupérer des données.
- Un dump de la base de données.

## Modalités de rendu

- Effectuer une pull request sur le repository pour soumettre ton projet.

