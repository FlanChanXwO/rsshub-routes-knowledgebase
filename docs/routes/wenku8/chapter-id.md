# 轻小说文库 - 章节

## Coverage
`index-only`

## Route
- Namespace: `wenku8`
- Namespace Name: `轻小说文库`
- Route Path: `/chapter/:id`
- Route Name: `章节`
- Example: `/wenku8/chapter/74`
- URL: `www.wenku8.net`
- Language: `zh-CN`
- Categories: `reading`
- Maintainers: `zsakvo`
- Source Location: `chapter.ts`
- Source Module: `() => import('@/routes/wenku8/chapter.ts')`

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
_None_

## Raw JSON
```json
{
  "categories": [
    "reading"
  ],
  "example": "/wenku8/chapter/74",
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
    "zsakvo"
  ],
  "module": "() => import('@/routes/wenku8/chapter.ts')",
  "name": "章节",
  "parameters": {
    "id": "小说 id, 可在对应小说页 URL 中找到"
  },
  "path": "/chapter/:id"
}
```
