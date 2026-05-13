# QooApp - Game Store - Notes

## Coverage
`index-only`

## Route
- Namespace: `qoo-app`
- Namespace Name: `QooApp`
- Route Path: `/apps/:lang?/note/:id`
- Route Name: `Game Store - Notes`
- Example: `/qoo-app/apps/en/note/7675`
- URL: `apps.qoo-app.com`
- Language: `zh-CN`
- Categories: `anime`
- Maintainers: `TonyRL`
- Source Location: `apps/note.ts`
- Source Module: `() => import('@/routes/qoo-app/apps/note.ts')`

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
  "example": "/qoo-app/apps/en/note/7675",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "apps/note.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/qoo-app/apps/note.ts')",
  "name": "Game Store - Notes",
  "parameters": {
    "id": "Game ID, can be found in URL",
    "lang": "Language, see the table above, empty means `中文`"
  },
  "path": "/apps/:lang?/note/:id"
}
```
