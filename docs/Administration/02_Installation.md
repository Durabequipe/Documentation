# Installation

## Requirements

* PHP 8.1 ou supérieur
* MySQL 5.7 ou supérieur

## Installation

### 1. Télécharger le code source

* Cloner le code source depuis [GitHub](https://github.com/Durabequipe/Administration)

### 2. Installer les dépendances

* Installer les dépendances avec [Composer](https://getcomposer.org/)

```bash
composer install
```

### 3. Configurer l'application

* Copier le fichier `.env.example` en `.env`

```bash
cp .env.example .env
```

* Configurer les variables d'environnement dans le fichier `.env`

### 4. Configurer la base de données

* Créer la base de données

```bash
php artisan migrate
```

### 5. Générer la clé d'application

* Générer la clé d'application

```bash
php artisan key:generate
```

### 6. Configurer les dossiers de stockage

* Créer les dossiers de stockage

```bash
mkdir -p storage/app/public/images
mkdir -p storage/app/public/thumbnails
mkdir -p storage/app/public/videos
```

### 7. Lancer le serveur

* Lancer le serveur

```bash
php artisan serve
```

