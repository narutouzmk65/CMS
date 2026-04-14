# 🌍 WorldTour — Documentation Technique WordPress (Blocs Gutenberg)

**WorldTour** est un site WordPress réalisé pour une **agence de voyage nationale**.  
Le site a été conçu **exclusivement avec les blocs natifs WordPress (éditeur Gutenberg)**, **sans extensions supplémentaires**, afin de garantir simplicité, stabilité et compatibilité maximale.

- 📆 **Date** : Avril 2025  
- 🏢 **Réalisation** : ESN Stesio  
- 🌐 **Site en ligne** : https://blog27143.wordpress.com/

---

## 📚 Sommaire

- Présentation du projet  
- Installation de WordPress  
- Utilisation des blocs WordPress  
- Structure du site  
- Navigation et menus  
- Gestion des rôles  
- Ajouter un voyage ou une antenne  
- Support et contact  

---

## 🎯 Présentation du projet

Le projet **WorldTour** vise à présenter :
- l’agence nationale,
- ses antennes locales,
- les voyages proposés,
via un site WordPress clair, structuré et facilement maintenable.

✅ Le site a été réalisé **sans plugins fonctionnels**, uniquement à l’aide :
- de l’éditeur **Gutenberg**,
- des **blocs WordPress par défaut**,
- et des fonctionnalités natives de WordPress.com.

---

## ⚙️ Installation de WordPress

Le projet est disponible :
- **en ligne** via WordPress.com (site public),
- **en local** sur un serveur `srv-lamp` pour les tests.

### Prérequis

| Élément | Détail |
|------|------|
| Navigateur | Chrome / Firefox / Edge |
| Serveur local | Apache + PHP + MySQL |
| Accès Internet | Requis pour WordPress.com |
| Outils | WinSCP, PuTTY |

---

### Installation en ligne (WordPress.com)

🌐 Site : https://blog27143.wordpress.com/

1. Créer un compte sur https://wordpress.com  
2. Choisir le **plan gratuit**  
3. Créer le site *WorldTour*  
4. Accéder au tableau de bord  

> 💡 Le site en ligne sert de **vitrine officielle**.

---

### Installation en local (srv-lamp)

- Accès : `http://srv-lamp/~identifiant/`
- Base de données : `identifiant_wp`
- Serveur BDD : `localhost`

⚠️ **Important**  
Le mot de passe administrateur WordPress ne peut **pas être réinitialisé**.

---

## 🧱 Utilisation des blocs WordPress (Gutenberg)

Le site utilise **uniquement les blocs natifs** :

### Blocs utilisés

| Bloc WordPress | Utilisation |
|-------------|-------------|
| Paragraphe | Textes descriptifs |
| Titre | Hiérarchisation du contenu |
| Image | Visuels des voyages / antennes |
| Galerie | Photos des destinations |
| Colonnes | Mise en page structurée |
| Boutons | Liens vers voyages / contact |
| Liste | Services, employés, départs |
| Tableau | Tarifs des voyages |
| Formulaire de contact | Bloc WordPress.com |

✅ Aucun plugin requis  
✅ Interface stable et légère  
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

Chaque antenne comprend :
- une présentation de la ville,
- les responsables,
- les employés (par rôle),
- une mise en page en blocs colonnes & images.

---

### Pages Voyages

Chaque page voyage contient :
- une présentation complète,
- une galerie photo (bloc Galerie),
- un **tableau de tarifs** (bloc Tableau),
- les durées (4j / 7j / 15j),
- les lieux de départ,
- un formulaire de contact.

---

## 🧭 Menus de navigation

Le menu principal est configuré via :

**Apparence → Menus**

- Accueil
- Nos Antennes (menu déroulant)
- Nos Voyages (menu déroulant)
- Contact

---

## 👥 Gestion des rôles

| Rôle | Accès |
|----|----|
| Administrateur | Gestion complète du site |
| Éditeur WorldTour | Modification du contenu |

Création d’un compte :
`Tableau de bord → Utilisateurs → Ajouter`

---

## ➕ Ajouter un voyage ou une antenne

### Ajouter un voyage

1. Dupliquer un modèle de page existant  
2. Modifier le contenu avec les blocs :
   - Titre
   - Paragraphe
   - Galerie
   - Tableau
3. Associer la page à **Nos Voyages**
4. Publier

---

### Ajouter une antenne

1. Dupliquer une page antenne existante  
2. Modifier les informations (ville, employés)  
3. Ajouter au menu **Nos Antennes**
4. Publier

---

## 🛟 Support et contact

- 📧 **Contact ESN Stesio** : f.bravais@gmail.com  
- 📚 Documentation WordPress : https://fr.wordpress.org/support/  

---

_Documentation officielle — Projet WorldTour_ by Reynaud Marlon and Guillermin Egido Esteban