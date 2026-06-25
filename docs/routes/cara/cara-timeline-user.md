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
  "heat": 15,
  "location": "timeline.ts",
  "maintainers": [
    "KarasuShin"
  ],
  "name": "Timeline",
  "parameters": {
    "user": "username"
  },
  "path": "/timeline/:user",
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
      "description": "Timeline - alayne - Powered by RSSHub",
      "errorAt": "2025-11-26T13:48:31.342Z",
      "errorMessage": "[GET] \"https://cara.app/explore\": 403 Forbidden\n",
      "id": "127385598208675840",
      "image": "https://cdn.cara.app/production/profiles/21e1de53-84c1-4167-9328-cacacc0f4804/1C7C9B2C-1519-4E22-9381-559B422076F6.jpg",
      "ownerUserId": null,
      "siteUrl": "https://cara.app/alayne/all",
      "title": "Timeline - alayne",
      "type": "feed",
      "url": "rsshub://cara/timeline/alayne"
    },
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
    }
  ]
}
```
