# Les ressources

L'API fonctionne principalement avec une seule resource.

## La clé d'API

### Obtenir une clé d'API

Pour obtenir une clé d'API, il faut se connecter à l'administration. La clé
se trouve dans la bar de menu en haut à gauche.

### Utiliser la clé d'API

Vous pouvez transmettre la clé d'API dans l'URL en paramètre ou dans le header.
```bash
curl -X GET "{{base-url}}/players?api_key={{api-key}}"
```

```bash
curl -X GET "{{base-url}}/players" -H "x-api-key: {{api-key}}"
```

### /players

Retourne la liste des projets vidéos.

#### Schéma

```json
[
  {
    "id": "STRING",
    "name": "STRING",
    "description": "STRING",
    "isActive": "BOOLEAN",
    "entrypointId": "STRING",
    "coverImage": "STRING",
    "thumbnailImage": "STRING",
    "videos": [
      {
        "VIDEO"
      }
    ]
  }
]

```

#### L'objet vidéo

```json
{
  "id": "STRING",
  "name": "STRING",
  "paths": [
    "STRING", // desktop path
    "STRING" // mobile path
  ],
  "thumbnails": [
    "STRING", // desktop path
    "STRING" // mobile path
  ],
  "animation": {
    "title": "STRING",
    "position": "STRING", // full|bottom
    "duration": "NUMBER" // in seconds
  },
  "interactions": [
    {
      "id": "STRING", // VIDEO ID
      "content": "STRING" // title of the interaction
    }
  ]
}
```




