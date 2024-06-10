# CV_JsonResume

Ce projet contient mon CV au format JSON, permettant une conversion facile et une utilisation dans divers contextes numériques. Il est basé sur le format [JSON Resume](https://jsonresume.org/), un standard ouvert pour les CV.

## Table des matières

- [📝 Introduction](#-introduction)
- [⚙️ Installation](#-installation)
- [🚀 Utilisation](#-utilisation)
- [📂 Structure du fichier JSON](#-structure-du-fichier-json)
- [🤝 Contribution](#-contribution)
- [📜 Licence](#-licence)

## 📝 Introduction

Ce dépôt contient mon CV sous forme de fichier JSON, conforme au standard JSON Resume. L'objectif est de fournir une représentation structurée et facilement lisible par des machines de mon parcours professionnel et académique, ainsi que de mes compétences.

## ⚙️ Installation

Pour utiliser ou afficher le CV, suivez ces étapes :

1. Clonez le dépôt sur votre machine locale :

   ```bash
   git clone https://github.com/N-BLET/CV_JsonResume.git
   ```

2. Naviguez dans le répertoire du projet :
   ```bash
   cd CV_JsonResume
   ```
3. Assurez-vous d'avoir Node.js installé. Si ce n'est pas le cas, vous pouvez le télécharger ici.

4. Installez le paquet resume-cli pour visualiser le CV :

```bash
npm install -g resume-cli
```

## 🚀 Utilisation

Pour afficher le CV, utilisez la commande suivante dans le répertoire du projet :

```bash
resume serve
```

Cela ouvrira une nouvelle fenêtre de navigateur affichant le CV dans un format lisible.

## 📂 Structure du fichier JSON

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

Pour plus de détails sur chaque section, consultez la [documentation officielle](https://jsonresume.org/schema/).
