# 少数派 sspai - 专栏

## Coverage
`index-only`

## Route
- Namespace: `sspai`
- Namespace Name: `少数派 sspai`
- Route Path: `/column/:id`
- Route Name: `专栏`
- Example: `/sspai/column/262`
- URL: `sspai.com`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `LogicJake`
- Source Location: `column.ts`
- Source Module: `() => import('@/routes/sspai/column.ts')`

## Description
_None_

## Parameters
- `id`: 专栏 id


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `sspai.com/column/:id`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/sspai/column/262",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "column.ts",
  "maintainers": [
    "LogicJake"
  ],
  "module": "() => import('@/routes/sspai/column.ts')",
  "name": "专栏",
  "parameters": {
    "id": "专栏 id"
  },
  "path": "/column/:id",
  "radar": [
    {
      "source": [
        "sspai.com/column/:id"
      ]
    }
  ]
}
```
