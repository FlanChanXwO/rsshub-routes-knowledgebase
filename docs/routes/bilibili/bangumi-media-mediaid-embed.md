# 哔哩哔哩 bilibili - 番剧

## Coverage
`index-only`

## Route
- Namespace: `bilibili`
- Namespace Name: `哔哩哔哩 bilibili`
- Route Path: `/bangumi/media/:mediaid/:embed?`
- Route Name: `番剧`
- Example: `/bilibili/bangumi/media/9192`
- URL: `www.bilibili.com`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `DIYgod, nuomi1`
- Source Location: `bangumi.ts`
- Source Module: `() => import('@/routes/bilibili/bangumi.ts')`

## Description
_None_

## Parameters
- `mediaid`: 番剧媒体 id, 番剧主页 URL 中获取
- `embed`: 默认为开启内嵌视频, 任意值为关闭


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportRadar`: false
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
  "example": "/bilibili/bangumi/media/9192",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": false,
    "supportScihub": false
  },
  "location": "bangumi.ts",
  "maintainers": [
    "DIYgod",
    "nuomi1"
  ],
  "module": "() => import('@/routes/bilibili/bangumi.ts')",
  "name": "番剧",
  "parameters": {
    "embed": "默认为开启内嵌视频, 任意值为关闭",
    "mediaid": "番剧媒体 id, 番剧主页 URL 中获取"
  },
  "path": "/bangumi/media/:mediaid/:embed?",
  "view": 3
}
```
