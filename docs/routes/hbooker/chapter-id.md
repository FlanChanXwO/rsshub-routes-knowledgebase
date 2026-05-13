# 欢乐书客 - 章节

## Coverage
`index-only`

## Route
- Namespace: `hbooker`
- Namespace Name: `欢乐书客`
- Route Path: `/chapter/:id`
- Route Name: `章节`
- Example: `/hbooker/chapter/100113279`
- URL: `hbooker.com`
- Language: `zh-CN`
- Categories: `reading`
- Maintainers: `keocheung`
- Source Location: `chapter.ts`
- Source Module: `() => import('@/routes/hbooker/chapter.ts')`

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
  - `hbooker.com/book/:id`

## Raw JSON
```json
{
  "categories": [
    "reading"
  ],
  "example": "/hbooker/chapter/100113279",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "chapter.ts",
  "maintainers": [
    "keocheung"
  ],
  "module": "() => import('@/routes/hbooker/chapter.ts')",
  "name": "章节",
  "parameters": {
    "id": "小说 id, 可在对应小说页 URL 中找到"
  },
  "path": "/chapter/:id",
  "radar": [
    {
      "source": [
        "hbooker.com/book/:id"
      ]
    }
  ]
}
```
