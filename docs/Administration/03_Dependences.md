# Dépendences

## Dépendences de l'application

L'application requires

* FFMPEG (https://www.ffmpeg.org/) installer sur le serveur pour générer les vignettes de vidéos.

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