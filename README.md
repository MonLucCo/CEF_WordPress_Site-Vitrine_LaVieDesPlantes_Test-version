# CEF_WordPress_Site-Vitrine_LaVieDesPlantes_Test-version

Etablissement en WordPress d'un site vitrine selon les spécifications du CEF.

Ce projet est développé localement avec Local WP. Ce guide vous expliquera comment configurer et utiliser ce projet sur votre machine locale.

## Sommaire

- [CEF\_WordPress\_Site-Vitrine\_LaVieDesPlantes\_Test-version](#cef_wordpress_site-vitrine_laviedesplantes_test-version)
  - [Sommaire](#sommaire)
  - [Prérequis](#prérequis)
  - [Installation](#installation)
    - [1. Cloner le repository](#1-cloner-le-repository)
    - [2. Importer le projet dans Local WP](#2-importer-le-projet-dans-local-wp)
    - [3. Configurer le fichier hosts](#3-configurer-le-fichier-hosts)
    - [4. Démarrer le site](#4-démarrer-le-site)
  - [Utilisation](#utilisation)
    - [Accéder à l'admin WordPress](#accéder-à-ladmin-wordpress)
    - [Développement](#développement)
    - [Déploiement](#déploiement)
  - [Contribuer](#contribuer)

## Prérequis

Avant de commencer, assurez-vous d'avoir installé les éléments suivants :

- [Local WP](https://localwp.com/)
- [Git](https://git-scm.com/)
- [Visual Studio Code (VSCode)](https://code.visualstudio.com/)

## Installation

### 1. Cloner le repository

Clonez ce repository sur votre machine locale en utilisant Git :

`git clone https://github.com/votre-utilisateur/votre-repository.git`
`cd votre-repository`

### 2. Importer le projet dans Local WP

1. Ouvrez Local WP.
2. Cliquez sur le signe plus (+) pour créer un nouveau site.
3. Sélectionnez l'option "Importer un site existant".
4. Choisissez le dossier du projet cloné (votre-repository) et suivez les instructions pour importer le site.

### 3. Configurer le fichier hosts

Local WP devrait configurer automatiquement votre fichier hosts. Si ce n'est pas le cas, ajoutez manuellement l'entrée suivante :

`127.0.0.1 votre-site.local`

### 4. Démarrer le site

1. Dans Local WP, sélectionnez votre site importé.
2. Cliquez sur "Démarrer le site".

Votre site WordPress devrait maintenant être accessible à l'adresse `http://votre-site.local`.

## Utilisation

### Accéder à l'admin WordPress

Pour accéder à l'interface d'administration de WordPress, allez à `http://votre-site.local/wp-admin` et connectez-vous avec les identifiants fournis lors de l'importation.

### Développement

Utilisez Visual Studio Code pour éditer les fichiers de votre projet. Vous pouvez ouvrir le dossier du projet dans VSCode et utiliser les fonctionnalités Git intégrées pour gérer les commits, les branches, et les push vers GitHub.

### Déploiement

Pour déployer votre site sur un hébergeur, vous pouvez utiliser des plugins comme [Duplicator](https://wordpress.org/plugins/duplicator/) ou [All-in-One WP Migration](https://wordpress.org/plugins/all-in-one-wp-migration/) pour exporter et importer votre site.

## Contribuer

Si vous souhaitez contribuer à ce projet, veuillez suivre les étapes suivantes :

1. Forkez ce repository.
2. Créez une branche pour votre fonctionnalité (git checkout -b feature/ma-fonctionnalité).
3. Commitez vos modifications (git commit -m 'Ajouter ma fonctionnalité').
4. Poussez votre branche (git push origin feature/ma-fonctionnalité).
5. Ouvrez une Pull Request.
