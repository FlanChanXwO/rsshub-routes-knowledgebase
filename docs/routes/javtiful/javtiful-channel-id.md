# Javtiful - Channel

## Coverage
`index-only`

## Route
- Namespace: `javtiful`
- Namespace Name: `Javtiful`
- Route Path: `/javtiful/channel/:id`
- Route Name: `Channel`
- Example: `/javtiful/channel/madonna`
- URL: `javtiful.com`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `huanfe1`
- Source Location: `channel.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: Channel name


## Features
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `javtiful.com/channel/:id`
  - `javtiful.com/channel/:id/*`
- `target`: `/channel/:id`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/javtiful/channel/madonna",
  "features": {
    "nsfw": true
  },
  "heat": 510,
  "location": "channel.ts",
  "maintainers": [
    "huanfe1"
  ],
  "name": "Channel",
  "parameters": {
    "id": "Channel name"
  },
  "path": "/channel/:id",
  "radar": [
    {
      "source": [
        "javtiful.com/channel/:id",
        "javtiful.com/channel/:id/*"
      ],
      "target": "/channel/:id"
    }
  ],
  "topFeeds": [
    {
      "description": " - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "66507508116600832",
      "image": "https://javtiful.com/media/categories/collection/8.jpg?width=140",
      "ownerUserId": null,
      "siteUrl": "https://javtiful.com/channel/FC2PPV",
      "title": "RSSHub",
      "type": "feed",
      "url": "rsshub://javtiful/channel/FC2PPV"
    },
    {
      "description": " - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "63624830978450432",
      "image": "https://javtiful.com/media/categories/collection/44.jpg?width=140",
      "ownerUserId": null,
      "siteUrl": "https://javtiful.com/channel/madonna",
      "title": "RSSHub",
      "type": "feed",
      "url": "rsshub://javtiful/channel/madonna"
    }
  ]
}
```
