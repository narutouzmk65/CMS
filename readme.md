# 🌍 WorldTour — Documentation Technique CMS WordPress

**WorldTour**  
Agence de voyage nationale  
Documentation technique du site WordPress  

- 📆 **Date** : Avril 2025  
- 🏢 **Réalisation** : ESN Stesio  
- 🌐 **Site en ligne** : https://blog27143.wordpress.com/

---

## 📚 Sommaire

1. [Présentation du projet](#-présentation-du-projet)
2. [Installation de WordPress](#-installation-de-wordpress)
   - [Prérequis](#prérequis)
   - [Installation en ligne (WordPress.com)](#installation-en-ligne-wordpresscom)
   - [Installation en local (srv-lamp)](#installation-en-local-srv-lamp)
3. [Extensions WordPress](#-extensions-wordpress)
4. [Navigation et structure du site](#-navigation-et-structure-du-site)
5. [Gestion des rôles et accès](#-gestion-des-rôles-et-accès)
6. [Ajouter un voyage ou une antenne](#-ajouter-un-voyage-ou-une-antenne)
7. [Support et contact](#-support-et-contact)

---

## 🎯 Présentation du projet

Le projet **WorldTour** consiste à mettre en place un site **WordPress** pour une agence de voyage nationale.  
Le site est disponible :

- ✅ **En ligne** via WordPress.com (vitrine publique)
- ✅ **En local** sur un serveur `srv-lamp` pour les tests et développements

👉 Toute modification doit être **testée en local** avant publication en ligne.

---

## ⚙️ Installation de WordPress

### Prérequis

| Équipement | Détail |
|-----------|-------|
| Navigateur | Chrome, Firefox ou Edge (version récente) |
| Accès Internet | Requis pour la version en ligne |
| Serveur local | `srv-lamp` – Apache / PHP / MySQL |
| Client FTP | WinSCP |
| Client SSH | PuTTY |
| Identifiants | ga26 → gh26 (mot de passe = identifiant) |

---

### Installation en ligne (WordPress.com)

🌐 **URL du site** : https://blog27143.wordpress.com/

#### Étapes
1. Accéder à https://wordpress.com
2. Cliquer sur **Commencer**
3. Créer un compte (email, utilisateur, mot de passe)
4. Choisir le **plan gratuit**
5. Nommer le site (`worldtour-agence`)
6. Valider l’email
7. Accéder au tableau de bord

> 💡 Le site en ligne sert de **vitrine publique uniquement**

---

### Installation en local (srv-lamp)

#### Configuration proxy
Ajouter une **exception proxy** pour le domaine `srv-lamp` depuis les paramètres réseau du navigateur.

#### Connexion SSH
- Hôte : `srv-lamp` ou `192.168.1.103`
- Port : `22`
- Type : SSH
- Client : PuTTY

⚠️ **Important**  
Le mot de passe administrateur WordPress ne peut **pas être réinitialisé**.  
👉 Note‑le immédiatement (ex : Trello).

#### Installation WordPress
1. Connexion WinSCP vers `srv-lamp`
2. Dossier : `public_html/wordpress/`
3. Accéder à :  
   `http://srv-lamp/~ga26/`
4. Configuration :
   - Base : `ga26_wp`
   - Utilisateur BDD : identifiant équipe
   - Mot de passe : identifiant équipe
   - Serveur : `localhost`
   - Préfixe : `wp_`

✅ Installation terminée

#### Base de données
- phpMyAdmin : http://srv-lamp/phpmyadmin/

---

## 🔌 Extensions WordPress

### Extensions utilisées

| Extension | Utilité |
|--------|--------|
| Yet Another Stars Rating | Notation par étoiles |
| Easy Pricing Tables | Grilles tarifaires |
| Contact Form 7 | Formulaire de contact |
| Envira Gallery | Galerie photos |

---

### Installation d’une extension
1. Tableau de bord → Extensions → Ajouter
2. Rechercher l’extension
3. Installer → Activer
4. Configurer

---

### Configuration clé

#### ⭐ Yet Another Stars Rating (YASR)
- 5 étoiles
- Votes visiteurs activés
- Shortcode :
```text
[yasr_visitor_votes size="medium" readonly="no"]