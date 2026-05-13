# 起点 - 讨论区

## Coverage
`index-only`

## Route
- Namespace: `qidian`
- Namespace Name: `起点`
- Route Path: `/forum/:id`
- Route Name: `讨论区`
- Example: `/qidian/forum/1010400217`
- URL: `qidian.com`
- Language: `zh-CN`
- Categories: `reading`
- Maintainers: `fuzy112, pseudoyu`
- Source Location: `forum.ts`
- Source Module: `() => import('@/routes/qidian/forum.ts')`

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
  "example": "/qidian/forum/1010400217",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "forum.ts",
  "maintainers": [
    "fuzy112",
    "pseudoyu"
  ],
  "module": "() => import('@/routes/qidian/forum.ts')",
  "name": "讨论区",
  "parameters": {
    "id": "小说 id, 可在对应小说页 URL 中找到"
  },
  "path": "/forum/:id",
  "radar": [
    {
      "source": [
        "book.qidian.com/info/:id"
      ]
    }
  ]
}
```
