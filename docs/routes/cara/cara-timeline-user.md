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
    },
    {
      "description": "Timeline - 127 - Powered by RSSHub",
      "errorAt": "2025-11-26T14:20:48.941Z",
      "errorMessage": "[GET] \"https://cara.app/explore\": 403 Forbidden\n",
      "id": "127386983426590720",
      "image": "https://cdn.cara.app/production/profiles/f1a02228-6fa6-408e-9f03-ce991a568ba1/A1670231-0D18-40F6-A51A-AE28A40F7278.jpg",
      "ownerUserId": null,
      "siteUrl": "https://cara.app/alonelee127/all",
      "title": "Timeline - 127",
      "type": "feed",
      "url": "rsshub://cara/timeline/alonelee127"
    }
  ]
}
```
