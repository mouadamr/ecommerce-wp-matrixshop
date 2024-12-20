# E-Commerce MatrixShop 🌵

## Description du projet
Ce projet consiste en un site e-commerce complet développé avec WordPress et WooCommerce. Le site propose une expérience utilisateur fluide, un design attractif, et des fonctionnalités essentielles pour une boutique en ligne moderne.  

**Type de boutique :** Vente de cactus décoratifs  
**Localisation :** Agadir, Maroc  

---

## Contenu du dépôt
- **Code source** : Les fichiers principaux du site WordPress (thèmes et plugins).
- **Base de données** : Un fichier SQL exporté contenant toutes les données du site.
- **README.md** : Instructions détaillées pour l'installation et la configuration du site.

---

## Prérequis
Avant de commencer, assurez-vous d'avoir les éléments suivants installés sur votre machine :
- PHP (7.4 ou plus récent)
- MySQL ou MariaDB
- Serveur local (Apache, Nginx ou via XAMPP/WAMP)
- Git

---

## Installation

### 1. Cloner le dépôt
Clonez ce dépôt sur votre machine locale :

git clone https://github.com/mouadamr/ecommerce-wp-matrixshop.git
Accédez au dossier du projet :

Copier le code
cd ecommerce-matrixshop

2. Importer la base de données
Ouvrez phpMyAdmin (ou un autre outil de gestion de base de données).
Créez une nouvelle base de données, par exemple : ecommerce_cactus.
Importez le fichier SQL situé dans le dossier database :
database/wordpress-database.sql

3. Configurer WordPress
Accédez au fichier wp-config.php dans le dossier htdocs ou racine du projet.
Modifiez les paramètres de connexion à la base de données :

Copier le code
define('DB_NAME', 'wordpress'); // Nom de la base de données
define('DB_USER', 'root'); // Utilisateur MySQL
define('DB_PASSWORD', ''); // Mot de passe MySQL
define('DB_HOST', 'localhost'); // Hôte
4. Lancer le site
Placez les fichiers WordPress dans le répertoire de votre serveur local (par exemple : htdocs pour XAMPP).
Ouvrez votre navigateur et accédez à http://localhost/ecommerce-matrixshop.


Fonctionnalités principales
Système de tri et filtrage : Tri par prix, popularité, etc.
Pages essentielles : Accueil, Boutique, À propos, Contact.
Personnalisation visuelle : Design moderne et responsive.
Identifiants administratifs
URL du tableau de bord : /wp-admin
Nom d'utilisateur : root
Mot de passe : root

Structure des fichiers:

ecommerce-wp-matrixshop/
├── database/
│   └── wordpress-database.sql
├── wp-content/
│   ├── themes/
│   ├── plugins/
├── .gitignore
└── README.md

Contributeurs
Nom de l'étudiant : [Mouad AAMER,Bader ALOULI,Mohamed Bouabidi]

Licence
Ce projet est sous licence MIT. Vous êtes libre de l'utiliser, de le modifier et de le partager.


