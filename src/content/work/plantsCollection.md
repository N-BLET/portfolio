---
title: Plants Collection
publishDate: 2024-02-28 00:00:00
img: /assets/screenshotLogin.jpg
img_alt: Page de login de l'application
description: |
  Première application dévéloppée nativement pour mobile avec l'utilisation du langage Kotlin et de l'IDE Android Studio.
tags:
  - Dev mobile
  - Kotlin
  - noSQL
---

## PlantsCollection 🪴

### <font color="purple">Présentation de l'application mobile</font> 📝
L'objectif principal de ce projet était de concevoir une application permettant aux utilisateurs d'accéder à une base de données d'informations sur les plantes et de gérer leur propre collection de plantes favorites. Cette application offre la possibilité de créer un compte utilisateur sécurisé pour une expérience personnalisée. Ce projet m'a permis également de me familiariser avec le langage Kotlin et avec l'IDE Android Studio.

### <font color="purple">Fonctionnalités Principales</font> ⚙️
L'application permet aux utilisateurs de :
- Parcourir et partager des informations sur une variété de plantes.
- Créer et gérer leur propre liste de plantes favorites pour un accès rapide aux informations de celles-ci.
- Ajouter de nouvelles plantes à la base de données de l'application pour enrichir la collection disponible.
- Créer et gérer un compte utilisateur sécurisé pour une expérience personnalisée.

### <font color="purple">Structure de l'Application</font> 🏗️
L'application est organisée autour de 3 activités principales, 3 fragments et une popup pour une expérience utilisateur fluide et intuitive.

##### Activités
1. **Page de Connexion :** Permet aux utilisateurs de se connecter à leur compte existant.
2. **Page de Création de Compte Utilisateur :** Permet aux nouveaux utilisateurs de créer un compte sécurisé.
3. **Page Principale :** Affiche les informations sur les plantes et permet d'accéder aux fonctionnalités principales de l'application.

##### Fragments
1. **Accueil :** Affiche deux RecyclerViews pour permettre aux utilisateurs de découvrir de nouvelles plantes et parcourir la collection complète.
2. **Collection Personnalisée :** Affiche une liste des plantes sélectionnées par l'utilisateur pour une consultation rapide.
3. **Compte Utilisateur :** Permet aux utilisateurs de gérer leurs informations de compte.

##### Popup
Une popup est utilisée pour faciliter l'ajout de nouvelles plantes à la collection de l'utilisateur.

### <font color="purple">Isolation de l'Application</font> 🛡️
L'utilisation de 3 activités distinctes vise à isoler efficacement les fonctionnalités de connexion et de création de compte pour une meilleure gestion et sécurité de l'application.

### <font color="purple">Technologies Utilisées</font> 🛠️
- Kotlin : Langage de programmation principal pour le développement de l'application.
- Android Studio : Environnement de développement intégré (IDE) pour Android.
- Firebase : Utilisé comme base de données pour stocker les informations sur les plantes et les comptes utilisateurs, offrant ainsi une connexion sécurisée et des fonctionnalités en temps réel.

### <font color="purple">Liens</font> 🔗

🎥 - <a href="https://1drv.ms/v/s!Anvag74D4iR_pw1UWG0P4lGPW1p3?e=eachA6" target="_blank">Lien de la vidéo de présentation de l'application mobile</a>

<img src="https://github.githubassets.com/images/icons/emoji/octocat.png" alt="GitHub" width="15" height="15"> - <a href="https://github.com/N-BLET/PlantsCollection/" target="_blank">Lien vers le repository GitHub de l'application mobile</a>