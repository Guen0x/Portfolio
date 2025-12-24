---
title: Graye
publishDate: 2025-12-24 00:00:00
img: /assets/graye-cover.png
img_alt: Interface de l'application Graye
description: |
  Développement d'une application mobile de recommandation de restaurants intelligente et adaptative utilisant React Native.
tags:
  - TypeScript
  - React Native
  - Expo
  - SQLite
  - Algorithme & IA
  - UX/UI Design
---

## Application de recommandation intelligente

Graye est une application mobile innovante développée dans le cadre d'un projet universitaire (SAE S5). L'objectif était de concevoir un outil capable non seulement de géolocaliser des restaurants, mais surtout d'apprendre des habitudes de l'utilisateur pour lui proposer des recommandations personnalisées via un algorithme adaptatif.

L'application accompagne l'utilisateur de la découverte (Onboarding) à la dégustation, en passant par la recherche filtrée et la visualisation sur carte.

### Fonctionnalités clés

* **IA Adaptative** : Un algorithme de scoring unique qui prend en compte les préférences déclarées, l'historique de navigation et le contexte (distance, budget) pour classer les restaurants.
* **Expérience Utilisateur Complète** : Onboarding personnalisé, recherche intuitive, et détails complets sur chaque établissement.
* **Technologie Hybride** : Utilisation de React Native et Expo pour un déploiement multi-plateforme (iOS, Android, Web).
* **Mode Hors-ligne** : Architecture "Offline-First" grâce à une base de données locale SQLite, permettant une utilisation fluide même sans connexion.

##### Points positifs

Architecture technique robuste utilisant TypeScript et une séparation claire (MVC) pour la maintenabilité.

Mise en place d'un algorithme de recommandation complexe prenant en compte de multiples variables (bonus préférences, pénalité distance, etc.).

Gestion avancée des données avec persistance locale (SQLite / AsyncStorage) et compatibilité multi-plateforme (Web & Mobile).

Interface soignée avec plus de 40 catégories visuelles dynamiques et une carte interactive.

##### Difficultés rencontrées / Challenges

La gestion de la géolocalisation et des permissions sur différentes plateformes (Android vs Web) a demandé une configuration fine.

L'optimisation de l'algorithme de recommandation pour qu'il reste performant avec un grand volume de données en local.

L'adaptation de certaines bibliothèques (comme la gestion des cartes) pour assurer une compatibilité totale entre l'environnement mobile natif et le web.

Voici le lien vers le dépôt GitHub du projet : [Graye sur GitHub](https://github.com/RobertGriffaton/SAES55)