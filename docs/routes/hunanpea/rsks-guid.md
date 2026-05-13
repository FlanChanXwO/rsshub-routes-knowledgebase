# 湖南人事考试网 - 公告

## Coverage
`index-only`

## Route
- Namespace: `hunanpea`
- Namespace Name: `湖南人事考试网`
- Route Path: `/rsks/:guid`
- Route Name: `公告`
- Example: `/hunanpea/rsks/2f1a6239-b4dc-491b-92af-7d95e0f0543e`
- URL: `rsks.hunanpea.com`
- Language: `zh-CN`
- Categories: `study`
- Maintainers: `TonyRL`
- Source Location: `rsks.ts`
- Source Module: `() => import('@/routes/hunanpea/rsks.ts')`

## Description
_None_

## Parameters
- `guid`: 分类 id，可在 URL 中找到


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
  - `rsks.hunanpea.com/Category/:guid/ArticlesByCategory.do`

## Raw JSON
```json
{
  "categories": [
    "study"
  ],
  "example": "/hunanpea/rsks/2f1a6239-b4dc-491b-92af-7d95e0f0543e",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "rsks.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/hunanpea/rsks.ts')",
  "name": "公告",
  "parameters": {
    "guid": "分类 id，可在 URL 中找到"
  },
  "path": "/rsks/:guid",
  "radar": [
    {
      "source": [
        "rsks.hunanpea.com/Category/:guid/ArticlesByCategory.do"
      ]
    }
  ]
}
```
