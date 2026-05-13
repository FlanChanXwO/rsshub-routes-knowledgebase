# QooApp - News

## Coverage
`index-only`

## Route
- Namespace: `qoo-app`
- Namespace Name: `QooApp`
- Route Path: `/news/:lang?`
- Route Name: `News`
- Example: `/qoo-app/news/en`
- URL: `apps.qoo-app.com`
- Language: `zh-CN`
- Categories: `anime`
- Maintainers: `TonyRL`
- Source Location: `news.ts`
- Source Module: `() => import('@/routes/qoo-app/news.ts')`

## Description
| 中文 | English |
| ---- | ------- |
|      | en      |

## Parameters
- `lang`: Language, see the table below, empty means `中文`


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
  "description": "| 中文 | English |\n| ---- | ------- |\n|      | en      |",
  "example": "/qoo-app/news/en",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "news.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/qoo-app/news.ts')",
  "name": "News",
  "parameters": {
    "lang": "Language, see the table below, empty means `中文`"
  },
  "path": "/news/:lang?"
}
```
