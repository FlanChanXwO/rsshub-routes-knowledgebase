# Javtiful - Actress

## Coverage
`index-only`

## Route
- Namespace: `javtiful`
- Namespace Name: `Javtiful`
- Route Path: `/javtiful/actress/:id`
- Route Name: `Actress`
- Example: `/javtiful/actress/akari-tsumugi`
- URL: `javtiful.com`
- Language: `_None_`
- Categories: `multimedia, popular`
- Maintainers: `huanfe1`
- Source Location: `actress.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: Actress name


## Features
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `javtiful.com/actress/:id`
  - `javtiful.com/actress/:id/*`
- `target`: `/actress/:id`

## Raw JSON
```json
{
  "categories": [
    "multimedia",
    "popular"
  ],
  "example": "/javtiful/actress/akari-tsumugi",
  "features": {
    "nsfw": true
  },
  "heat": 12440,
  "location": "actress.ts",
  "maintainers": [
    "huanfe1"
  ],
  "name": "Actress",
  "parameters": {
    "id": "Actress name"
  },
  "path": "/actress/:id",
  "radar": [
    {
      "source": [
        "javtiful.com/actress/:id",
        "javtiful.com/actress/:id/*"
      ],
      "target": "/actress/:id"
    }
  ],
  "topFeeds": [
    {
      "description": " - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "63617818932634624",
      "image": "https://javtiful.com/media/categories/actress/THUMB-ACTRESS-271-6438402B2B69B.jpg?class=tmbactpage",
      "ownerUserId": null,
      "siteUrl": "https://javtiful.com/actress/akari-tsumugi",
      "title": "RSSHub",
      "type": "feed",
      "url": "rsshub://javtiful/actress/akari-tsumugi"
    },
    {
      "description": " - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "75560870348182528",
      "image": "https://javtiful.com/media/categories/actress/THUMB-ACTRESS-414-64370447C77C0.jpg?class=tmbactpage",
      "ownerUserId": null,
      "siteUrl": "https://javtiful.com/actress/mikami-yua",
      "title": "RSSHub",
      "type": "feed",
      "url": "rsshub://javtiful/actress/mikami-yua"
    }
  ]
}
```
