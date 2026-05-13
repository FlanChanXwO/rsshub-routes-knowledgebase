# 起点 - 作品章节

## Coverage
`index-only`

## Route
- Namespace: `qidian`
- Namespace Name: `起点`
- Route Path: `/chapter/:id`
- Route Name: `作品章节`
- Example: `/qidian/chapter/1010400217`
- URL: `qidian.com`
- Language: `zh-CN`
- Categories: `reading`
- Maintainers: `fuzy112, pseudoyu`
- Source Location: `chapter.ts`
- Source Module: `() => import('@/routes/qidian/chapter.ts')`

## Description
_None_

## Parameters
- `id`: 小说 id, 可在对应小说页 URL 中找到


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
  - `book.qidian.com/info/:id`

## Raw JSON
```json
{
  "categories": [
    "reading"
  ],
  "example": "/qidian/chapter/1010400217",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "chapter.ts",
  "maintainers": [
    "fuzy112",
    "pseudoyu"
  ],
  "module": "() => import('@/routes/qidian/chapter.ts')",
  "name": "作品章节",
  "parameters": {
    "id": "小说 id, 可在对应小说页 URL 中找到"
  },
  "path": "/chapter/:id",
  "radar": [
    {
      "source": [
        "book.qidian.com/info/:id"
      ]
    }
  ],
  "view": 5
}
```
