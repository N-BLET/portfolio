---
title: CV_JsonResume
publishDate: 2024-06-10 00:00:00
img: /assets/screenshotCV.png
img_alt: Page d'accueil du site
description: |
  CV formaté en JSON pour une utilisation numérique facilitée.
tags:
  - JSON
  - GitHub Action
  - JSON Resume Exporter
---

## Projet de CV au format JSON 📄

### <font color="purple">Présentation du projet</font> 📝

Ce projet contient mon CV au format JSON, permettant une conversion facile et une utilisation dans divers contextes numériques. Il est basé sur le format [JSON Resume](https://jsonresume.org/), un standard ouvert pour les CV. C'est un moyen efficace, évolutif et rapide pour maintenir un CV en ligne à jour.

### <font color="purple">Objectif du projet</font> 🎯

L'objectif est de fournir une représentation structurée et facilement lisible par des machines de mon parcours professionnel et académique, ainsi que de mes compétences.

### <font color="purple">Génération du fichier JSON depuis LinkedIn</font> 🔄

Pour générer le fichier `resume.json` à partir de votre profil LinkedIn, vous pouvez utiliser le plugin Chrome <a href="https://chromewebstore.google.com/detail/json-resume-exporter/caobgmmcpklomkcckaenhjlokpmfbdec" target="_blank">JSON Resume Exporter</a>. Ce plugin simplifie l'exportation des données de votre profil LinkedIn au format JSON, compatible avec ce projet. Ainsi, vous n'avez plus que votre profil LinkedIn à maintenir à jour et utiliser ce plugin pour générer le fichier Json et ainsi répercuter les modifications sur votre CV en ligne.

### <font color="purple">Intégration et Déploiement Continus (CI/CD)</font> 🚀

Pour aller plus loin dans le principe d'automatisation, j'ai également mis en place un GitHub Action. Ainsi l'intégration et le déploiement se font automatiquement.

1. **Fichier de configuration GitHub Actions** :

   - Le fichier de configuration se trouve dans le dossier `.github/workflows` et est nommé `github-ci.yml`.

2. **Récupération du fichier Json** :

   - Je génère en amont mon fichier resume.json. Puis j'exécute les différentes étapes pour terminer par le git push qui lance la génération du fichier resume.html qui sera renommé en index.html puis déplacer.

3. **Déploiement automatique** :
   - Le CV est automatiquement déployé sur une GitHub pages et redirigé grâce au CNAME vers mon VPS à l'adresse suivante cv.nicolasblet.fr

### <font color="purple">Structure du fichier JSON</font> 📂

Le fichier `resume.json` suit la structure recommandée par le standard JSON Resume. Voici un aperçu de sa structure :

- `basics`: Informations de base telles que le nom, l'email, le site web, le résumé.
- `work`: Expériences professionnelles.
- `volunteer`: Expériences bénévoles.
- `education`: Parcours académique.
- `awards`: Récompenses et distinctions.
- `publications`: Publications.
- `skills`: Compétences.
- `languages`: Langues parlées.
- `interests`: Centres d'intérêt.
- `references`: Références.

Pour plus de détails sur chaque section, consultez la <a href="https://jsonresume.org/schema/" target="_blank">documentation officielle</a>.

### <font color="purple">Liens</font> 🔗

🌐 - <a href="https://cv.nicolasblet.fr" target="_blank">Lien vers mon CV en ligne</a>

<img src="https://github.githubassets.com/images/icons/emoji/octocat.png" alt="GitHub" width="15" height="15"> - <a href="https://github.com/N-BLET/CV_JsonResume" target="_blank">Lien vers le repository GitHub du projet</a>
