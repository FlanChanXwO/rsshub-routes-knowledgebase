# Cara - Timeline

## Coverage
`index-only`

## Route
- Namespace: `cara`
- Namespace Name: `Cara`
- Route Path: `/cara/timeline/:user`
- Route Name: `Timeline`
- Example: `/cara/timeline/fengz`
- URL: `cara.app`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `KarasuShin`
- Source Location: `timeline.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `user`: username


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `cara.app/:user`
  - `cara.app/:user/*`
- `target`: `/timeline/:user`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/cara/timeline/fengz",
  "heat": 14,
  "location": "timeline.ts",
  "maintainers": [
    "KarasuShin"
  ],
  "name": "Timeline",
  "parameters": {
    "user": "username"
  },
  "path": [
    "/timeline/:user"
  ],
  "radar": [
    {
      "source": [
        "cara.app/:user",
        "cara.app/:user/*"
      ],
      "target": "/timeline/:user"
    }
  ],
  "topFeeds": [
    {
      "description": "Timeline - Requinoesis - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "131924534067985408",
      "image": "https://cdn.cara.app/production/profiles/3c4bf5ef-7d4e-4165-b65f-6dc781acf326/pu.png",
      "ownerUserId": null,
      "siteUrl": "https://cara.app/requinoesis/all",
      "title": "Timeline - Requinoesis",
      "type": "feed",
      "url": "rsshub://cara/timeline/requinoesis"
    },
    {
      "description": "Timeline - Emilia Cantor - Powered by RSSHub",
      "errorAt": "2025-11-26T13:56:52.009Z",
      "errorMessage": "[GET] \"https://cara.app/explore\": 403 Forbidden\n",
      "id": "127386620806396928",
      "image": "https://cdn.cara.app/production/profiles/1b141d8a-1c2d-46d7-8f24-ce74f14907be/B5C13DC8-F4EF-434D-8228-168A280EF68F.jpg",
      "ownerUserId": null,
      "siteUrl": "https://cara.app/emiliacantor/all",
      "title": "Timeline - Emilia Cantor",
      "type": "feed",
      "url": "rsshub://cara/timeline/emiliacantor"
    }
  ]
}
```
