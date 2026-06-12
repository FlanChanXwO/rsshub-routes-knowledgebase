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
      "description": "Timeline - Feng Zhu - Powered by RSSHub",
      "errorAt": "2025-11-26T12:33:50.034Z",
      "errorMessage": "[GET] \"https://cara.app/explore\": 403 \n",
      "id": "63189426042807297",
      "image": "https://cdn.cara.app/production/profiles/d5ba55be-a9af-4ce4-9b3a-0747165de742/feng_headshot_01.jpg",
      "ownerUserId": null,
      "siteUrl": "https://cara.app/fengz/all",
      "title": "Timeline - Feng Zhu",
      "type": "feed",
      "url": "rsshub://cara/timeline/fengz"
    },
    {
      "description": "Timeline - alayne - Powered by RSSHub",
      "errorAt": "2025-11-26T13:48:31.342Z",
      "errorMessage": "[GET] \"https://cara.app/explore\": 403 \n",
      "id": "127385598208675840",
      "image": "https://cdn.cara.app/production/profiles/21e1de53-84c1-4167-9328-cacacc0f4804/1C7C9B2C-1519-4E22-9381-559B422076F6.jpg",
      "ownerUserId": null,
      "siteUrl": "https://cara.app/alayne/all",
      "title": "Timeline - alayne",
      "type": "feed",
      "url": "rsshub://cara/timeline/alayne"
    }
  ]
}
```
