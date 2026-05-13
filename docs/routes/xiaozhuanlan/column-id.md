# 小专栏 - 专栏

## Coverage
`index-only`

## Route
- Namespace: `xiaozhuanlan`
- Namespace Name: `小专栏`
- Route Path: `/column/:id`
- Route Name: `专栏`
- Example: `/xiaozhuanlan/column/olddriver-selection`
- URL: `xiaozhuanlan.com`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `TonyRL`
- Source Location: `column.ts`
- Source Module: `() => import('@/routes/xiaozhuanlan/column.ts')`

## Description
_None_

## Parameters
- `id`: 专栏 ID，可在专栏页 URL 中找到


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
  - `xiaozhuanlan.com/:id`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/xiaozhuanlan/column/olddriver-selection",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "column.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/xiaozhuanlan/column.ts')",
  "name": "专栏",
  "parameters": {
    "id": "专栏 ID，可在专栏页 URL 中找到"
  },
  "path": "/column/:id",
  "radar": [
    {
      "source": [
        "xiaozhuanlan.com/:id"
      ]
    }
  ]
}
```
