# 🪐 Cosmotek

### Interface de ravitaillement galactique

**CY Tech – préING2 – 2025/2026**

---

## 🎯 Description du projet

**Cosmotek** est une application web multi-utilisateurs simulant un système de restauration destiné aux explorateurs galactiques.

L’application couvre l’ensemble du cycle de commande :
de la sélection des produits par l’explorateur jusqu’à la livraison finale par navette.

### 🧩 Architecture – Phase #1

La première phase repose sur :

* Une **interface graphique statique** développée en **HTML5**
* Une **charte graphique immersive** centralisée dans un unique fichier CSS
* Une **adaptation multi-terminaux** (ordinateur, tablette, smartphone)

---

## ⚙️ Fonctionnalités

### 🖥️ 1. Interfaces de navigation (Front-end)

Modules visuels développés pour **3 profils utilisateurs** :

#### 👨‍🚀 Client

* Accueil
* Consultation de la carte des produits
* Inscription, Connexion et profil
* Système de notation

#### 🍳 Restaurateur

* Interface adaptée aux tablettes
* Préparation des commandes

#### 🚀 Livreur

* Interface adaptée aux téléphones mobiles

#### 💻 Administrateur

* Interface permettant de voir les dernieres commandes

---

### 🔐 2. Gestion des données et accès

* **Authentification**

  * Page de connexion
  * Page d’inscription

* **Profil Client**

  * Historique des expériences passées
  * Système de points de fidélité

---

## 🛠️ Installation & Exécution

### 1️⃣ Cloner le dépôt

```bash
git clone https://github.com/Snowsurf-007/Cosmotek_web
cd Cosmotek_web
```

### 2️⃣ Lancer l’application

* Le fichier `accueil.html` constitue le point d’entrée utilisateur

### 📱 Simulation Mobile (Livreur)

1. Ouvrir les outils de développement (`F12`)
2. Activer le mode **responsive**
3. Sélectionner une taille pour les smartphones (360 x 740 par exemple)

---

## 📂 Structure du projet

* `accueil.html` → Page d’accueil présentant le nom du restaurant, une barre de recherche et une sélection de plats (populaires).

* `admin.html` → Interface administrateur permettant de consulter la liste des utilisateurs et les dernières commandes.

* `carte.html` → Page de consultation complète de la carte avec barre de recherche et filtres par catégorie (types de plats).

* `inscription.html` → Page d’inscription contenant le formulaire client (nom, prénom, adresse, téléphone, mail, mot de passe…).

* `connexion.html` → Page de connexion avec formulaire d’authentification classique.

* `profil.html` → Page profil client affichant les informations personnelles et le compte fidélité.

* `commande.html` → Interface restaurateur affichant les commandes en attente de préparation et celles en cours de livraison.

* `livraison.html` → Interface livreur optimisée mobile affichant les informations de livraison (adresse, code, téléphone, commentaires…).

* `avis.html` → Page permettant au client de noter la livraison et la qualité des produits reçus.

* `style.css` → Fichier unique regroupant toute la charte graphique et les styles communs.

### 📄 Documentation

* **Charte graphique** : PNG définissant l’univers visuel
* **Rapport de mission – Phase #1** :

  * Répartition des tâches
  * Problèmes rencontrés
  * Solutions mises en place

---

## 👥 Auteurs

* **Ibrahima TRAORE**
* **Hugo TRENY**
* **Lucien LEHEUDRE--EPSTEIN**

---

## 🌌 Univers graphique

Charte visuelle immersive inspirée :
**Boite techno / Néon / Interface futuriste**
