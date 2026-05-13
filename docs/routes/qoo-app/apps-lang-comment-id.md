# QooApp - Game Store - Review

## Coverage
`index-only`

## Route
- Namespace: `qoo-app`
- Namespace Name: `QooApp`
- Route Path: `/apps/:lang?/comment/:id`
- Route Name: `Game Store - Review`
- Example: `/qoo-app/apps/en/comment/7675`
- URL: `apps.qoo-app.com`
- Language: `zh-CN`
- Categories: `anime`
- Maintainers: `TonyRL`
- Source Location: `apps/comment.ts`
- Source Module: `() => import('@/routes/qoo-app/apps/comment.ts')`

## Description
| 中文 | English | 한국어 | Español | 日本語 | ไทย | Tiếng Việt |
| ---- | ------- | ------ | ------- | ------ | --- | ---------- |
|      | en      | ko     | es      | ja     | th  | vi         |

## Parameters
- `lang`: Language, see the table below, empty means `中文`
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
  "description": "| 中文 | English | 한국어 | Español | 日本語 | ไทย | Tiếng Việt |\n| ---- | ------- | ------ | ------- | ------ | --- | ---------- |\n|      | en      | ko     | es      | ja     | th  | vi         |",
  "example": "/qoo-app/apps/en/comment/7675",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "apps/comment.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/qoo-app/apps/comment.ts')",
  "name": "Game Store - Review",
  "parameters": {
    "id": "Game ID, can be found in URL",
    "lang": "Language, see the table below, empty means `中文`"
  },
  "path": "/apps/:lang?/comment/:id"
}
```
