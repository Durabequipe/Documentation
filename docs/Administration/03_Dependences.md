# Dépendences

## Dépendences de l'application

L'application requires les dépendences suivantes :

* FFMPEG (https://www.ffmpeg.org/) pour générer les vignettes de vidéos.

#### Installation de FFMPEG

### Linux

```bash
sudo apt-get install ffmpeg
```

### Mac
```bash
brew install ffmpeg
```

Pour que FFMPEG fonctionne correctement, il faut modifier le fichier .env et ajouter la ligne suivante :

```bash
FFMPEG_BIN="/opt/homebrew/bin"
```