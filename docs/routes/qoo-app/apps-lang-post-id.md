# QooApp - Game Store - Article

## Coverage
`index-only`

## Route
- Namespace: `qoo-app`
- Namespace Name: `QooApp`
- Route Path: `/apps/:lang?/post/:id`
- Route Name: `Game Store - Article`
- Example: `/qoo-app/apps/en/post/7675`
- URL: `apps.qoo-app.com`
- Language: `zh-CN`
- Categories: `anime`
- Maintainers: `TonyRL`
- Source Location: `apps/post.ts`
- Source Module: `() => import('@/routes/qoo-app/apps/post.ts')`

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
  "example": "/qoo-app/apps/en/post/7675",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "apps/post.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/qoo-app/apps/post.ts')",
  "name": "Game Store - Article",
  "parameters": {
    "id": "Game ID, can be found in URL",
    "lang": "Language, see the table above, empty means `中文`"
  },
  "path": "/apps/:lang?/post/:id"
}
```
