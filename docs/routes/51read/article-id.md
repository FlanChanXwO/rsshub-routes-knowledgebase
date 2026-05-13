# 51Read - 章节

## Coverage
`index-only`

## Route
- Namespace: `51read`
- Namespace Name: `51Read`
- Route Path: `/article/:id`
- Route Name: `章节`
- Example: `/51read/article/152685`
- URL: `m.51read.org`
- Language: `zh-CN`
- Categories: `reading`
- Maintainers: `lazwa34`
- Source Location: `article.ts`
- Source Module: `() => import('@/routes/51read/article.ts')`

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
  - `m.51read.org/xiaoshuo/:id`
- `target`: `/article/:id`
### Rule 2
- `source`:
  - `51read.org/xiaoshuo/:id`
- `target`: `/article/:id`

## Raw JSON
```json
{
  "categories": [
    "reading"
  ],
  "example": "/51read/article/152685",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "article.ts",
  "maintainers": [
    "lazwa34"
  ],
  "module": "() => import('@/routes/51read/article.ts')",
  "name": "章节",
  "parameters": {
    "id": "小说 id, 可在对应小说页 URL 中找到"
  },
  "path": "/article/:id",
  "radar": [
    {
      "source": [
        "m.51read.org/xiaoshuo/:id"
      ],
      "target": "/article/:id"
    },
    {
      "source": [
        "51read.org/xiaoshuo/:id"
      ],
      "target": "/article/:id"
    }
  ],
  "url": "m.51read.org"
}
```
