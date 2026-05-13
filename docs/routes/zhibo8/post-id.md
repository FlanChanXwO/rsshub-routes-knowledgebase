# 直播吧 - 回帖

## Coverage
`index-only`

## Route
- Namespace: `zhibo8`
- Namespace Name: `直播吧`
- Route Path: `/post/:id`
- Route Name: `回帖`
- Example: `/zhibo8/post/3050708`
- URL: `zhibo8.cc`
- Language: `zh-CN`
- Categories: `bbs`
- Maintainers: `LogicJake`
- Source Location: `post.ts`
- Source Module: `() => import('@/routes/zhibo8/post.ts')`

## Description
_None_

## Parameters
- `id`: 帖子 id，可在帖子 URL 找到


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
  "example": "/zhibo8/post/3050708",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "post.ts",
  "maintainers": [
    "LogicJake"
  ],
  "module": "() => import('@/routes/zhibo8/post.ts')",
  "name": "回帖",
  "parameters": {
    "id": "帖子 id，可在帖子 URL 找到"
  },
  "path": "/post/:id"
}
```
