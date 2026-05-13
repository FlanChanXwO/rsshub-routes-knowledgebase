# ArtStation - Artist Profolio

## Coverage
`index-only`

## Route
- Namespace: `artstation`
- Namespace Name: `ArtStation`
- Route Path: `/:handle`
- Route Name: `Artist Profolio`
- Example: `/artstation/wlop`
- URL: `www.artstation.com`
- Language: `en`
- Categories: `picture`
- Maintainers: `TonyRL`
- Source Location: `user.ts`
- Source Module: `() => import('@/routes/artstation/user.ts')`

## Description
_None_

## Parameters
- `handle`: Artist handle, can be found in URL


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.artstation.com/:handle`

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "example": "/artstation/wlop",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "user.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/artstation/user.ts')",
  "name": "Artist Profolio",
  "parameters": {
    "handle": "Artist handle, can be found in URL"
  },
  "path": "/:handle",
  "radar": [
    {
      "source": [
        "www.artstation.com/:handle"
      ]
    }
  ]
}
```
