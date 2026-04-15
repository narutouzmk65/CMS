# 🌍 WorldTour — TP WordPress
**Découverte et mise en œuvre d’un système de gestion de contenus (CMS)**

🔗 Site en ligne : https://blog27143.wordpress.com/

Ce fichier constitue **l’unique documentation officielle du projet WorldTour**.  
Il répond intégralement au **sujet de TP “Système de gestion de contenus”**, au **cahier des charges**, et décrit **le site WordPress tel qu’il est réellement implémenté**.

---

## 📚 Sommaire

- [1. Contexte et objectifs du projet](#1-contexte-et-objectifs-du-projet)
- [2. Présentation générale du site WorldTour](#2-présentation-générale-du-site-worldtour)
- [3. Accès au site](#3-accès-au-site)
  - [3.1 Version en ligne](#31-version-en-ligne)
  - [3.2 Version locale (srv-lamp)](#32-version-locale-srv-lamp)
- [4. Architecture globale du site](#4-architecture-globale-du-site)
  - [4.1 En-tête (Header)](#41-en-tête-header)
  - [4.2 Pied de page (Footer)](#42-pied-de-page-footer)
- [5. Pages et composantes du site](#5-pages-et-composantes-du-site)
  - [5.1 Page Accueil](#51-page-accueil)
  - [5.2 Pages Antennes](#52-pages-antennes)
  - [5.3 Pages Voyages](#53-pages-voyages)
  - [5.4 Page Contact](#54-page-contact)
- [6. Modèles de pages (pages vierges)](#6-modèles-de-pages-pages-vierges)
- [7. Navigation et menus](#7-navigation-et-menus)
- [8. Gestion des accès et des rôles](#8-gestion-des-accès-et-des-rôles)
- [9. Modification et maintenance du site](#9-modification-et-maintenance-du-site)
  - [9.1 Modifier une page existante](#91-modifier-une-page-existante)
  - [9.2 Ajouter un nouveau voyage](#92-ajouter-un-nouveau-voyage)
  - [9.3 Ajouter une nouvelle antenne](#93-ajouter-une-nouvelle-antenne)
- [10. Bonnes pratiques et erreurs à éviter](#10-bonnes-pratiques-et-erreurs-à-éviter)
- [11. Critères d’évaluation](#11-critères-dévaluation)
- [12. Support et ressources](#12-support-et-ressources)

---

## 1. Contexte et objectifs du projet

WorldTour est une **agence de voyage nationale** proposant des **circuits touristiques organisés**.  
Jusqu’à présent, chaque antenne disposait de son propre site, ce qui ne correspondait plus à l’image souhaitée par l’agence.

Le projet a pour objectif de :
- centraliser l’ensemble des voyages sur une **plateforme unique**,
- proposer un **site vitrine simple à maintenir**,
- permettre à l’agence de modifier le contenu **sans compétence technique**.

La solution retenue est **WordPress**, utilisé comme **CMS**.

---

## 2. Présentation générale du site WorldTour

Le site WorldTour est un **site vitrine WordPress** composé :
- d’une page de présentation de l’agence,
- d’une page par antenne,
- d’une page par voyage,
- d’une page contact.

L’ensemble du contenu est géré via **l’éditeur de blocs WordPress (Gutenberg)**.

---

## 3. Accès au site

### 3.1 Version en ligne

👉 https://blog27143.wordpress.com/

- Site public
- Version finale
- Accessible à tout utilisateur

---

### 3.2 Version locale (srv-lamp)

Serveur : `srv-lamp` ou `192.168.1.103`

Accès navigateur :
http://srv-lamp/~ga26/
La version locale permet :
- les tests,
- la modification sans risque,
- l’expérimentation avant publication.

---

## 4. Architecture globale du site

### 4.1 En-tête (Header)

Présent sur toutes les pages :
- Nom du site **WorldTour**
- Menu de navigation principal
- Adaptation mobile / ordinateur

---

### 4.2 Pied de page (Footer)

Présent sur toutes les pages :
- Informations générales
- Cohérence graphique
- Structure simple

---

## 5. Pages et composantes du site

### 5.1 Page Accueil

Contenu :
- Présentation générale de WorldTour
- Texte descriptif
- Images illustratives
- Mise en avant des voyages et antennes

Blocs utilisés :
- Titre
- Paragraphe
- Image

---

### 5.2 Pages Antennes

Antennes présentes :
- Tarbes
- Toulouse
- Auch

Structure d’une antenne :
- Nom de la ville
- Coordonnées
- Responsables
- Employés par rôle
- Images
- Description

Toutes les antennes utilisent **le même modèle de page**.

---

### 5.3 Pages Voyages

Voyages disponibles :
- Islande
- Dubaï
- République Dominicaine

Chaque page voyage contient obligatoirement :
- Descriptif du voyage
- Galerie photos (minimum 4 images)
- Tableau des tarifs :
  - seul / couple / famille
  - durée : 4, 7, 15 jours
- Lieux de départ
- Invitation à contacter l’agence

---

### 5.4 Page Contact

- Informations de contact
- Texte explicatif
- Moyen de prise de contact

---

## 6. Modèles de pages (pages vierges)

Des pages modèles permettent :
- l’ajout rapide de nouveaux voyages,
- l’ajout de nouvelles antennes,
- une cohérence sur l’ensemble du site.

---

## 7. Navigation et menus

Configuration :
**Apparence > Menus**

Menu principal :
- Accueil
- Nos Antennes
  - Tarbes
  - Toulouse
  - Auch
- Nos Voyages
  - Islande
  - Dubaï
  - République Dominicaine
- Contact

Objectif : **accès en 2 clics maximum**.

---

## 8. Gestion des accès et des rôles

- **Administrateur**
  - Accès complet
  - Réservé à l’ESN Stesio
- **Éditeur WorldTour**
  - Modification du contenu uniquement

---

## 9. Modification et maintenance du site

### 9.1 Modifier une page existante

1. Tableau de bord WordPress
2. Pages > Toutes les pages
3. Ouvrir la page
4. Modifier les blocs
5. Cliquer sur **Mettre à jour**

---

### 9.2 Ajouter un nouveau voyage

1. Dupliquer un voyage existant
2. Modifier le titre, le texte, les images
3. Adapter le tableau des tarifs
4. Publier
5. Ajouter le voyage au menu

---

### 9.3 Ajouter une nouvelle antenne

1. Dupliquer une antenne existante
2. Modifier les informations
3. Publier
4. Ajouter au menu

---

## 10. Bonnes pratiques et erreurs à éviter

- Toujours enregistrer avec **Mettre à jour**
- Ne pas supprimer une page sans certitude
- Garder une structure identique
- Tester en local avant publication
- Noter soigneusement le mot de passe administrateur

---

## 11. Critères d’évaluation

### Documentation (8 points)
- Précision et complétude
- Clarté
- Qualité rédactionnelle

### Site WordPress (12 points)
- Pages attendues complètes
- Qualité des contenus
- Esthétique
- Convivialité

---

## 12. Support et ressources

📖 Documentation WordPress :  
https://fr.wordpress.org/support/

📧 Contact projet :  
f.bravais@gmail.com