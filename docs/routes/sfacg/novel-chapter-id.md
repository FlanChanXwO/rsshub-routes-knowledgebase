# SF 轻小说 - 章节

## Coverage
`index-only`

## Route
- Namespace: `sfacg`
- Namespace Name: `SF 轻小说`
- Route Path: `/novel/chapter/:id`
- Route Name: `章节`
- Example: `/sfacg/novel/chapter/672431`
- URL: `book.sfacg.com`
- Language: `zh-CN`
- Categories: `reading`
- Maintainers: `keocheung`
- Source Location: `novel-chapter.ts`
- Source Module: `() => import('@/routes/sfacg/novel-chapter.ts')`

## Description
_None_

## Parameters
- `id`: 小说 id, 可在对应小说页 URL 中找到


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
  - `book.sfacg.com/Novel/:id/*`

## Raw JSON
```json
{
  "categories": [
    "reading"
  ],
  "example": "/sfacg/novel/chapter/672431",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "novel-chapter.ts",
  "maintainers": [
    "keocheung"
  ],
  "module": "() => import('@/routes/sfacg/novel-chapter.ts')",
  "name": "章节",
  "parameters": {
    "id": "小说 id, 可在对应小说页 URL 中找到"
  },
  "path": "/novel/chapter/:id",
  "radar": [
    {
      "source": [
        "book.sfacg.com/Novel/:id/*"
      ]
    }
  ]
}
```
