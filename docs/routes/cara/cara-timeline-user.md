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
    },
    {
      "description": "Timeline - Olevus Art - Powered by RSSHub",
      "errorAt": "2025-11-26T13:56:41.091Z",
      "errorMessage": "[GET] \"https://cara.app/explore\": 403 Forbidden\n",
      "id": "127387927078266880",
      "image": "https://cdn.cara.app/production/profiles/328e10c7-adef-4eba-b86a-d847a0c7cb6a/17BE1A54-C420-41BC-954C-EB9123B82F2D.jpg",
      "ownerUserId": null,
      "siteUrl": "https://cara.app/olevusart/all",
      "title": "Timeline - Olevus Art",
      "type": "feed",
      "url": "rsshub://cara/timeline/olevusart"
    }
  ]
}
```
