```json
{
  "id": "project_id",
  "entrypointId": "video_id",
  "graph": {
    "nodes": [
      {
        "value": {
          "videosPaths": ["desktop_path","mobile_path"],
          "interactionPosition": "FULL | BOTTOM",
          "popupDuration": "number_second",
          "text": "string_question_to_ask | null",
          "interactions": [
            {
              "id": "video_id"
              "content": "html_content",
              "videosPaths": ["desktop_path","mobile_path"],
            },
          ],
        },
        "adjacents": ["video_id","video_id","video_id"],
      },
    ],
  }
}

```


Commentaires 

