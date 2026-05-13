# 阿基米德 FM - 播客

## Coverage
`index-only`

## Route
- Namespace: `ajmide`
- Namespace Name: `阿基米德 FM`
- Route Path: `/:id`
- Route Name: `播客`
- Example: `/ajmide/10603594`
- URL: `m.ajmide.com`
- Language: `zh-CN`
- Categories: `multimedia`
- Maintainers: `Fatpandac`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/ajmide/index.ts')`

## Description
_None_

## Parameters
- `id`: 播客 id，可以从播客页面 URL 中找到


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
    "multimedia"
  ],
  "example": "/ajmide/10603594",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.ts",
  "maintainers": [
    "Fatpandac"
  ],
  "module": "() => import('@/routes/ajmide/index.ts')",
  "name": "播客",
  "parameters": {
    "id": "播客 id，可以从播客页面 URL 中找到"
  },
  "path": "/:id",
  "view": 4
}
```
