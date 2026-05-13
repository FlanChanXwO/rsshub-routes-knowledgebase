# CCC 創作集 - 漫畫

## Coverage
`index-only`

## Route
- Namespace: `creative-comic`
- Namespace Name: `CCC 創作集`
- Route Path: `/book/:id/:coverOnly?/:quality?`
- Route Name: `漫畫`
- Example: `/creative-comic/book/117`
- URL: `creative-comic.tw`
- Language: `zh-TW`
- Categories: `anime`
- Maintainers: `TonyRL`
- Source Location: `book.tsx`
- Source Module: `() => import('@/routes/creative-comic/book.tsx')`

## Description
_None_

## Parameters
- `id`: 漫畫 ID，可在 URL 中找到
- `coverOnly`: 僅獲取封面，非 `true` 時將獲取**全部**頁面，預設 `true`
- `quality`: 閱讀品質，標準畫質 `1`，高畫質 `2`，預設 `1`


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
  - `creative-comic.tw/book/:id/*`
- `target`: `/:id`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/creative-comic/book/117",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "book.tsx",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/creative-comic/book.tsx')",
  "name": "漫畫",
  "parameters": {
    "coverOnly": "僅獲取封面，非 `true` 時將獲取**全部**頁面，預設 `true`",
    "id": "漫畫 ID，可在 URL 中找到",
    "quality": "閱讀品質，標準畫質 `1`，高畫質 `2`，預設 `1`"
  },
  "path": "/book/:id/:coverOnly?/:quality?",
  "radar": [
    {
      "source": [
        "creative-comic.tw/book/:id/*"
      ],
      "target": "/:id"
    }
  ]
}
```
