# 🌍 WorldTour — Documentation Technique WordPress (Blocs Gutenberg)

**WorldTour** est un site WordPress réalisé pour une **agence de voyage nationale**.  
Le site a été conçu **exclusivement avec les blocs natifs WordPress (éditeur Gutenberg)**, **sans aucune extension**, afin de garantir simplicité, stabilité et compatibilité avec WordPress.com.

- 📆 **Date** : Avril 2025  
- 🏢 **Réalisation** :Marlon and Esteban  
- 🌐 **Site en ligne** : https://blog27143.wordpress.com/

---

## 📚 Sommaire

- [Présentation du projet](#-présentation-du-projet)
- [Installation de WordPress](#️-installation-de-wordpress)
  - [Installation en ligne (WordPress.com)](#installation-en-ligne-wordpresscom)
  - [Installation en local (srv-lamp)](#installation-en-local-srv-lamp)
- [Utilisation des blocs WordPress](#-utilisation-des-blocs-wordpress)
- [Structure du site](#-structure-du-site)
- [Navigation et menus](#-navigation-et-menus)
- [Gestion des rôles](#-gestion-des-rôles)
- [Ajouter un voyage ou une antenne](#-ajouter-un-voyage-ou-une-antenne)
- [Support et contact](#-support-et-contact)

---

## 🎯 Présentation du projet

Le projet **WorldTour** consiste à créer et administrer un site WordPress pour une agence de voyage nationale.

Le site permet de :
- présenter l’agence,
- afficher les antennes locales,
- mettre en avant les voyages proposés,
- faciliter la prise de contact.

✅ Le site est conçu **sans plugins**, uniquement avec :
- l’éditeur **Gutenberg**,
- les **blocs WordPress natifs**,
- les fonctionnalités standard de WordPress.com.

---

## ⚙️ Installation de WordPress

Le projet existe sous deux formes :
- **Version en ligne** (site officiel)
- **Version locale** (tests et modifications)

---

### Installation en ligne (WordPress.com)

🌐 Site officiel : https://blog27143.wordpress.com/

Étapes :
1. Création du site sur WordPress.com
2. Choix du plan gratuit
3. Configuration du nom et des pages
4. Accès au tableau de bord

> 💡 Le site en ligne sert de **vitrine publique**.  
> Les tests sont effectués en local avant mise en production.

---

### Installation en local (srv-lamp)

- Serveur : Apache / PHP / MySQL
- Accès : `http://srv-lamp/~identifiant/`
- Base de données : `identifiant_wp`

⚠️ **Important**  
Le mot de passe administrateur WordPress **ne peut pas être réinitialisé**.  
Il doit être sauvegardé dès la création du site.

---

## 🧱 Utilisation des blocs WordPress

Le site WorldTour utilise **uniquement les blocs natifs** fournis par WordPress.

### Blocs utilisés

- **Titre** : hiérarchisation du contenu
- **Paragraphe** : textes descriptifs
- **Image** : visuels antennes et voyages
- **Galerie** : photos des destinations
- **Colonnes** : mise en page structurée
- **Tableau** : grilles tarifaires
- **Liste** : employés, départs, services
- **Boutons** : navigation et appels à l’action
- **Formulaire de contact** : bloc WordPress.com

✅ Aucun plugin externe  
✅ Site léger et stable  
✅ Compatible WordPress.com

---

## 🧭 Structure du site

### Architecture générale

- **Accueil**
- **Nos Antennes**
  - Tarbes
  - Toulouse
  - Auch
- **Nos Voyages**
  - Dubaï
  - Islande
  - République Dominicaine
- **Contact**

---

### Pages Antennes

Chaque page antenne contient :
- présentation de la ville,
- responsables,
- employés (par rôle),
- images et mise en page en colonnes.

---

### Pages Voyages

Chaque page voyage inclut :
- descriptif détaillé,
- galerie photo (min. 4 images),
- tableau de tarifs (4j / 7j / 15j),
- lieux de départ,
- formulaire de contact.

---

## 🧭 Navigation et menus

Le menu principal est configuré via :

**Tableau de bord → Apparence → Menus**

Il contient :
- Accueil
- Nos Antennes (menu déroulant)
- Nos Voyages (menu déroulant)
- Contact

---

## 👥 Gestion des rôles

| Rôle | Droits |
|----|----|
| Administrateur | Gestion complète du site |
| Éditeur WorldTour | Modification du contenu |

Création d’un utilisateur :
`Tableau de bord → Utilisateurs → Ajouter`

---

## ➕ Ajouter un voyage ou une antenne

### Ajouter un voyage

1. Dupliquer une page voyage existante
2. Modifier le contenu via les blocs
3. Ajuster les tarifs et images
4. Associer la page à **Nos Voyages**
5. Publier

---

### Ajouter une antenne

1. Dupliquer une page antenne
2. Modifier les informations (ville, employés)
3. Ajouter au menu **Nos Antennes**
4. Publier

---

## 🛟 Support et contact

- 📧 **Contact ESN Stesio** : f.bravais@gmail.com  
- 📚 Support WordPress : https://fr.wordpress.org/support/

---

_Documentation officielle — Projet WorldTour — Avril 2025_by Marlon and Esteban