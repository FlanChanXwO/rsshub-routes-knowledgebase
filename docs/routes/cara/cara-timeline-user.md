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
      "description": "Timeline - Rodrigo Goulao de Sousa - Powered by RSSHub",
      "errorAt": "2025-11-26T14:00:44.455Z",
      "errorMessage": "[GET] \"https://cara.app/explore\": 403 Forbidden\n",
      "id": "127384139525444608",
      "image": "https://cdn.cara.app/production/profiles/34966e18-5684-4d9d-afab-838babacdc30/465BAAB1-DDE7-42C3-9A1F-E078CF2DA69B.jpg",
      "ownerUserId": null,
      "siteUrl": "https://cara.app/rodrigogsousa/all",
      "title": "Timeline - Rodrigo Goulao de Sousa",
      "type": "feed",
      "url": "rsshub://cara/timeline/rodrigogsousa"
    },
    {
      "description": "Timeline - Feng Zhu - Powered by RSSHub",
      "errorAt": "2025-11-26T12:33:50.034Z",
      "errorMessage": "[GET] \"https://cara.app/explore\": 403 Forbidden\n",
      "id": "63189426042807297",
      "image": "https://cdn.cara.app/production/profiles/d5ba55be-a9af-4ce4-9b3a-0747165de742/feng_headshot_01.jpg",
      "ownerUserId": null,
      "siteUrl": "https://cara.app/fengz/all",
      "title": "Timeline - Feng Zhu",
      "type": "feed",
      "url": "rsshub://cara/timeline/fengz"
    }
  ]
}
```
