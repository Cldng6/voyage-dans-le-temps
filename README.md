# 🚨 Avertissement Équipe DEV !!!!
    🚨 ATTENTION ! Ce projet est collaboratif. Merci de respecter les consignes suivantes pour éviter tout conflit ou perte de données.

    ❌ NE JAMAIS travailler directement sur la branche main.

    ✅ Toujours créer une branche pour chaque nouvelle fonctionnalité ou correction.

    🔁 Mettre à jour régulièrement votre branche locale depuis main pour rester synchro.

    🧪 Créer une Pull Request pour toute modification que vous voulez intégrer à main.

    👀 Faire relire et valider votre PR par au moins un autre membre avant de merger.

    💬 Communiquez entre vous si vous travaillez sur des parties similaires pour éviter les doublons.

    👉 En cas de doute, posez la question à l’équipe AVANT de pousser vos modifications.

    Merci de suivre ces règles pour garantir un bon workflow et un projet propre ! 💪

## 📌 1. Chacun clone le projet
    
    git clone https://github.com/Cldng6/voyage-dans-le-temps.git

### 👉 Une fois le projet cloné, va dans le dossier du projet cloné :
    
    cd voyage-dans-le-temps

## 📌 2. Travail en branches
### 🔧 Chacun crée sa propre branche à partir de main :

    git checkout main
    git pull origin main
    git checkout -b feature/nom-fonctionnalite
    git push -u origin feature/nom-fonctionnalite
    Remplace "nom-fonctionnalite" par un nom clair, par ex : feature/login, bugfix/navbar, etc.

## 📌 3. Chacun travaille sur sa branche
### 💾 Chacun fait ses commits et push régulièrement :

    git add .
    git commit -m "Ajout de la fonctionnalité X"
    git push



# 🎯 Objectif du MVP
    
    Créer une version fonctionnelle du site qui présente le parc, ses attractions principales, les infos pratiques, et donne envie de venir.

## 🌐 Structure du Site (MVP)
### 🏠 Page d’accueil

    But : Présenter le parc et son concept
    Titre accrocheur :
    "Parc Temporellia – Voyagez à travers les époques !"
    Hero Banner :
    Image immersive (machine temporelle / époques qui se mélangent)
    Pitch :
    "Explorez le passé, vivez le présent, imaginez le futur… Le seul parc d’attractions qui vous transporte à travers le temps !"
    Bouton CTA :
    "Découvrez nos attractions" (lien vers la section suivante)

## 🎢 Attractions principales

    Divisées par catégorie d’âge :

## 👶 Pour les enfants

    Mini Dinos Express
    L’Atelier des Inventeurs
    
## 👨‍👩‍👧 Pour toute la famille

    Tunnel Temporel
    Escape Time
    
## 👾 Pour les ados & adultes

    Cyber Coaster VR
    Mission 3024 (laser game futuriste)
    
## 🎨 Chaque attraction avec :

    Une image
    Un titre
    Une courte description
    Une icône d’âge conseillé
    
## 🕓 Infos pratiques

    Tarifs (enfants, adultes, familles)
    Horaires d’ouverture
    Accès & plan d’accès (avec carte)
    Restauration & services

## 📅 Réserver sa visite

    Formulaire simple :
    Nombre de personnes
    Date
    E-mail
    Bouton : “Réserver mon voyage temporel”

## 📸 Galerie / ambiance

    4 à 6 images du parc (décors épiques, enfants émerveillés, etc.)

## 📬 Footer / bas de page

    Liens rapides : Accueil, Attractions, Réservation
    Réseaux sociaux
    Contact
    Mentions légales

## ✅ Fonctionnalités essentielles du MVP

    Responsive design (mobile/tablette/ordi)
    Navigation fluide
    Formulaire de contact ou réservation
    Présentation des attractions par âge
    Design immersif qui évoque le voyage dans le temps

## Arborescence v1

    RACINE DU SITE
    │
    ├── HEADER (sur toutes les pages)
    │   ├── Logo (Accueil)
    │   ├── Menu navigation
    │   │   ├── Acceuil
    │   │   ├── Attractions
    │   │   ├── Infos pratiques
    │   │   ├── Tarifs & Réservation
    │   │   └── À propos
    │   └── Connexion / Inscription
    │
    ├── PAGES PRINCIPALES
    │   ├── Accueil
    │   ├── Attractions
    │   ├── Informations pratiques
    │   ├── Tarifs & Réservation
    │   └── À propos du parc
    │
    ├── ESPACE UTILISATEUR
    │   ├── Inscription / Connexion
    │   └── Profil utilisateur
    │       ├── Infos personnelles
    │       ├── Réservations
    │       └── Préférences
    │
    ├── FOOTER (sur toutes les pages)
    │   ├── Liens utiles
    │   ├── Réseaux sociaux
    │   ├── Newsletter
    │   └── Contact
    │
    └── BACK-OFFICE ADMINISTRATEUR
        ├── Tableau de bord
        ├── Gestion attractions
        ├── Gestion réservations
        ├── Gestion tarifs
        ├── Gestion utilisateurs
        └── Configuration du site




## Arborescence v2

    Vayage-dans-le-temps
    │
    ├── css
    │   ├── about.css
    │   ├── attractions.css
    │   ├── checkout.css
    │   ├── contact.css
    │   ├── forgot-password.css
    │   ├── login.css
    │   ├── news.css
    │   ├── privacy-policy.css
    │   ├── profile.css
    │   ├── reset-password.css
    │   ├── signup.css
    │   └── terms.css
    │
    ├── images
    │   ├── favicon
    │   │   └──
    │   │
    │   └── logo
    │       └──
    │
    ├── pages
    │   ├── about
    │   ├── attractions.html
    │   ├── checkout.html
    │   ├── contact.html
    │   ├── forgot-password.html
    │   ├── login.html
    │   ├── news.html
    │   ├── privacy-policy.html
    │   ├── profile.html
    │   ├── reset-password.html
    │   ├── signup.html
    │   └── terms.html
    │
    ├──README.md
    └── index.html
