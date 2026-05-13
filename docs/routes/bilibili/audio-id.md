# 哔哩哔哩 bilibili - 歌单

## Coverage
`index-only`

## Route
- Namespace: `bilibili`
- Namespace Name: `哔哩哔哩 bilibili`
- Route Path: `/audio/:id`
- Route Name: `歌单`
- Example: `/bilibili/audio/10624`
- URL: `www.bilibili.com`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `LogicJake`
- Source Location: `audio.ts`
- Source Module: `() => import('@/routes/bilibili/audio.ts')`

## Description
_None_

## Parameters
- `id`: 歌单 id, 可在歌单页 URL 中找到


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
    "social-media"
  ],
  "example": "/bilibili/audio/10624",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "audio.ts",
  "maintainers": [
    "LogicJake"
  ],
  "module": "() => import('@/routes/bilibili/audio.ts')",
  "name": "歌单",
  "parameters": {
    "id": "歌单 id, 可在歌单页 URL 中找到"
  },
  "path": "/audio/:id"
}
```
