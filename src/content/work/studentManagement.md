---
title: Student Management
publishDate: 2024-05-22 00:00:00
img: /assets/studentManagement.png
img_alt: Page d'accueil d'un site de gestion d'une école
description: |
  Application web basée sur une structure N-Tier développée en C# avec l'IDE Visual Studio.
tags:
  - C#
  - Visual Studio
  - ASP.NET
---

## Projet de Gestion des Élèves 📚

Ce projet consiste en une application de bureau développée en C# permettant de gérer des élèves. L'application offre une interface utilisateur conviviale pour créer, modifier, afficher et supprimer des élèves.

### <font color="purple">Architecture</font> 🏗️

L'application est conçue selon une architecture N-tiers, séparant les différentes couches logiques du projet (présentation, logique métier, et accès aux données) pour une meilleure maintenabilité et évolutivité.
L'architecture N-tiers pour une application web offre plusieurs avantages clés : elle permet une séparation claire des préoccupations, améliorant ainsi la maintenabilité et la modularité. Cette structure facilite la réutilisation des composants, optimise les performances et la scalabilité en permettant de gérer chaque couche indépendamment, et renforce la sécurité en isolant les différentes couches. En somme, cette approche assure une application web robuste, flexible et évolutive.

<a href="https://github.com/N-BLET/ArchiNtier/blob/main/SchemaArchi/ArchitNtiersSite.pdf" target="_blank">Schéma de l'architecture du site</a>

### <font color="purple">Fonctionnalités</font> ⚙️

- **Gestion des élèves :**
  - Création de nouveaux élèves
  - Modification des informations des élèves existants
  - Affichage de la liste des élèves
  - Suppression des élèves

### <font color="purple">API Web</font> 🌐

Pour compléter l'application de gestion des élèves, j'ai développé une API Web en ASP.NET Core. Cette API permet d'accéder aux données des élèves via des endpoints RESTful, facilitant ainsi l'intégration avec d'autres systèmes ou applications. Grâce à cette API, les opérations CRUD (Create, Read, Update, Delete) peuvent être effectuées de manière sécurisée et efficace, améliorant l'interopérabilité et offrant une flexibilité accrue pour l'accès aux données. L'API est construite en respectant les meilleures pratiques en termes de sécurité et de performance, garantissant une communication fluide et sécurisée avec la base de données. De plus, la documentation interactive de l'API est disponible via Swagger, permettant aux développeurs de tester facilement les différentes fonctionnalités offertes par l'API.

### <font color="purple">Liens</font> 🔗

🎥 - <a href="https://1drv.ms/v/s!Anvag74D4iR_qCLzYqI4kW4RTedZ" target="_blank">Lien de la vidéo de présentation de l'application</a>

🎥 - <a href="https://1drv.ms/v/s!Anvag74D4iR_qCPgQ1HPZ-X_MdEm" target="_blank">Lien de la vidéo de présentation de l'API Web</a>

<img src="https://github.githubassets.com/images/icons/emoji/octocat.png" alt="GitHub" width="15" height="15"> - <a href="https://github.com/N-BLET/TdCDA/" target="_blank">Lien vers le repository GitHub du l'application</a>
