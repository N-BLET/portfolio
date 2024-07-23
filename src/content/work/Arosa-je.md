---
title: Arosa-je
publishDate: 2024-07-03 00:00:00
img: /assets/arosaje.png
img_alt: Image de présentation d'Arosa-je
description: |
  Arosa-je est une application mobile innovante qui met en relation les propriétaires de plantes avec des botanistes experts pour des conseils personnalisés, tout en favorisant une dimension communautaire.
tags:
  - React
  - NestJS
  - Prisma
---

## Arosa-je 🌱

### <font color="green">Présentation de l'application mobile</font> 📝

Arosa-je propose de mettre en relation les propriétaires de plantes avec des botanistes experts et des gardiens, afin d'obtenir facilement des conseils personnalisés pour entretenir et faire prospérer leurs plantes. Cette application mobile vise à créer une communauté autour du végétal, où chacun peut partager son savoir-faire. Les utilisateurs pourront poster des photos de leurs plantes nécessitant des soins, et recevoir en retour les précieux conseils de botanistes confirmés.

### <font color="green">Fonctionnalités Principales</font> ⚙️

L'application permet aux utilisateurs de :

- Poster des photos de leurs plantes pour obtenir des conseils personnalisés de la part de botanistes experts.
- Partager des photos pour le suivi des plantes.
- Utiliser une dimension communautaire pour échanger des conseils et des expériences.
- Planifier la garde de leurs plantes avec des gardiens.

### <font color="green">Structure de l'Application</font> 🏗️

L'application est organisée autour des modules suivants :

- **Front-end :** Utilise React, Tailwind et Vite pour une interface utilisateur réactive et moderne.
- **Back-end :** Basé sur NestJS, Prisma et SQLite pour une gestion efficace des données et des requêtes.
- **Containerisation :** Utilisation de Docker pour le déploiement et la mise à l'échelle.

### <font color="green">Tests</font> 🧪

Les tests jouent un rôle crucial pour garantir la qualité et la fiabilité de l'application :

- **Tests unitaires :** Écrits avec Jest pour le back-end et React Testing Library pour le front-end.
- **Tests d'intégration :** Utilisation de Cypress pour les tests de bout en bout, garantissant que toutes les parties de l'application fonctionnent ensemble correctement.
- **Tests de performance :** Mise en place de Lighthouse pour surveiller et optimiser les performances de l'application.

### <font color="green">CI/CD</font> 🚀

Pour optimiser notre processus de développement et de déploiement, nous avons mis en place une automatisation CI/CD (Continuous Integration/Continuous Deployment) en utilisant GitHub Actions. Voici comment nous avons structuré ce processus :

### Automatisation du backend avec GitHub Actions

Pour le backend, nous avons créé un workflow GitHub Actions qui automatise la construction et la mise à disposition de notre image Docker sur Docker Hub :

- Lorsqu'un nouveau tag est poussé sur la branche principale de notre dépôt GitHub, le workflow se déclenche automatiquement.
- GitHub Actions récupère le code source du backend et le place dans un environnement de construction.
- Le workflow lance la construction de l'image Docker en utilisant le Dockerfile présent dans le dépôt.
- Une fois l'image construite avec succès, elle est poussée sur notre compte Docker Hub, avec le tag du commit.
- L'image Docker est ainsi disponible sur Docker Hub, prête à être déployée sur notre infrastructure.

### Automatisation du frontend avec GitHub Actions

Pour le frontend, un workflow similaire est utilisé pour automatiser la construction de notre application mobile en un fichier APK :

- Lorsqu'un nouveau tag est poussé sur la branche principale de notre dépôt GitHub, le workflow se déclenche automatiquement.
- GitHub Actions récupère le code source du frontend et le place dans un environnement de construction.
- Le workflow lance la construction de l'application mobile en utilisant gradle.
- Signature du fichier APK.
- Upload du fichier APK dans les artefacts de GitHub.
- Création d'une Release avec le fichier APK.

En utilisant GitHub Actions pour automatiser notre CI/CD, nous avons amélioré notre processus de développement et de déploiement, réduisant les risques d'erreurs, accélérant les cycles de livraison et assurant une qualité constante de notre application.

### <font color="green">RGPD</font> 🔒

Conformité avec le Règlement Général sur la Protection des Données (RGPD) :

- **Gestion des données personnelles :** Collecte minimale des données personnelles des utilisateurs, avec consentement explicite pour chaque type de donnée collectée.
- **Droit à l'oubli :** Les utilisateurs peuvent demander la suppression de leurs données personnelles à tout moment.
- **Récupération des données :** Les utilisateurs peuvent demander la récupération des différentes informations les concernant présentes dans notre base de données.
- **Sécurisation des données :** Utilisation de techniques de chiffrement avancées pour protéger les données des utilisateurs, en conformité avec les normes RGPD.

### <font color="green">Technologies Utilisées</font> 🛠️

- **Front-end :** React, Tailwind, Vite.
- **Back-end :** NestJS, Prisma, SQLite.
- **Containerisation :** Docker.
- **Outils de développement :** Capacitor pour transformer le site web en application mobile.

### <font color="green">Présentation de l'équipe</font> 👥

Notre équipe est composée de 4 étudiants en développement logiciel, chacun apportant ses compétences uniques pour mener à bien ce projet :

- **Arnaud Gaydamour**
- **Tristan Gottschalk**
- **Dylan D'Antonio**
- **Nicolas Blet**

### <font color="green">Contexte du projet</font> 🎓

Ce projet a été réalisé dans le cadre d'une mise en situation professionnelle pour l'obtention de mon bachelor. Il a permis de mettre en pratique les connaissances acquises durant la formation et de travailler sur un projet complet, de la conception à la mise en production.

### <font color="green">Liens</font> 🔗

🎥 - <a href="https://1drv.ms/v/s!Anvag74D4iR_qDJxa92k4uxhw9RD?e=OIdd95" target="_blank">Lien de présentation de projet et du maquettage de l'application</a>

🎥 - <a href="https://1drv.ms/v/s!Anvag74D4iR_qDALF-uh6PKFYOfl?e=kGr2eP" target="_blank">Lien de présentation de la conteneurisation, ainsi que les différents tests et la CI/CD qui sont mis en place pour réaliser ce projet.</a>

🎥 - <a href="https://1drv.ms/v/s!Anvag74D4iR_qDFDAJxN_awEQ9qr?e=FI7EYB" target="_blank">Lien de présentation de la conception de la base de données, des composants métiers, de notre documentation « Swagger » et de notre prise en compte du Règlement Général sur la Protection des Données (RGPD) de notre application</a>

🎥 - <a href="https://1drv.ms/v/s!Anvag74D4iR_qDS5nKOwOHFcn68m" target="_blank">Lien de la vidéo de présentation de notre application</a>

📂 - <a href="https://1drv.ms/b/s!Anvag74D4iR_qDObiB5a4pYl4-a9?e=LFBr16" target="_blank">Lien vers le livrable de notre projet</a>

<img src="https://github.githubassets.com/images/icons/emoji/octocat.png" alt="GitHub" width="15" height="15"> - <a href="https://github.com/epsi-mspr-antd/frontend" target="_blank">Lien vers le repository GitHub du front-end</a><br>
<img src="https://github.githubassets.com/images/icons/emoji/octocat.png" alt="GitHub" width="15" height="15"> - <a href="https://github.com/epsi-mspr-antd/backend" target="_blank">Lien vers le repository GitHub du back-end</a>
