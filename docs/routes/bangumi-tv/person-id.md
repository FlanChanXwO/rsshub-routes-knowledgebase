# Bangumi 番组计划 - 现实人物的新作品

## Coverage
`index-only`

## Route
- Namespace: `bangumi.tv`
- Namespace Name: `Bangumi 番组计划`
- Route Path: `/person/:id`
- Route Name: `现实人物的新作品`
- Example: `/bangumi.tv/person/32943`
- URL: `bangumi.tv`
- Language: `zh-CN`
- Categories: `anime`
- Maintainers: `ylc395`
- Source Location: `person/index.ts`
- Source Module: `() => import('@/routes/bangumi.tv/person/index.ts')`

## Description
_None_

## Parameters
- `id`: 人物 id, 在人物页面的地址栏查看


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
  - `bgm.tv/person/:id`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/bangumi.tv/person/32943",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "person/index.ts",
  "maintainers": [
    "ylc395"
  ],
  "module": "() => import('@/routes/bangumi.tv/person/index.ts')",
  "name": "现实人物的新作品",
  "parameters": {
    "id": "人物 id, 在人物页面的地址栏查看"
  },
  "path": "/person/:id",
  "radar": [
    {
      "source": [
        "bgm.tv/person/:id"
      ]
    }
  ]
}
```
