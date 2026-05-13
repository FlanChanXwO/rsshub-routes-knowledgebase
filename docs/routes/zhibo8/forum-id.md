# 直播吧 - 子论坛

## Coverage
`index-only`

## Route
- Namespace: `zhibo8`
- Namespace Name: `直播吧`
- Route Path: `/forum/:id`
- Route Name: `子论坛`
- Example: `/zhibo8/forum/8`
- URL: `zhibo8.cc`
- Language: `zh-CN`
- Categories: `bbs`
- Maintainers: `LogicJake`
- Source Location: `forum.ts`
- Source Module: `() => import('@/routes/zhibo8/forum.ts')`

## Description
_None_

## Parameters
- `id`: 子论坛 id，可在子论坛 URL 找到


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "example": "/zhibo8/forum/8",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "forum.ts",
  "maintainers": [
    "LogicJake"
  ],
  "module": "() => import('@/routes/zhibo8/forum.ts')",
  "name": "子论坛",
  "parameters": {
    "id": "子论坛 id，可在子论坛 URL 找到"
  },
  "path": "/forum/:id"
}
```
