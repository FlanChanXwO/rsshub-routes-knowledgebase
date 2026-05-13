# QooApp - Game Store - Cards

## Coverage
`index-only`

## Route
- Namespace: `qoo-app`
- Namespace Name: `QooApp`
- Route Path: `/apps/:lang?/card/:id`
- Route Name: `Game Store - Cards`
- Example: `/qoo-app/apps/en/card/7675`
- URL: `apps.qoo-app.com`
- Language: `zh-CN`
- Categories: `anime`
- Maintainers: `TonyRL`
- Source Location: `apps/card.ts`
- Source Module: `() => import('@/routes/qoo-app/apps/card.ts')`

## Description
_None_

## Parameters
- `lang`: Language, see the table above, empty means `中文`
- `id`: Game ID, can be found in URL


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/qoo-app/apps/en/card/7675",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "apps/card.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/qoo-app/apps/card.ts')",
  "name": "Game Store - Cards",
  "parameters": {
    "id": "Game ID, can be found in URL",
    "lang": "Language, see the table above, empty means `中文`"
  },
  "path": "/apps/:lang?/card/:id"
}
```
