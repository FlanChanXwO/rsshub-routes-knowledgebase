# 哔哩哔哩 bilibili - 视频弹幕

## Coverage
`index-only`

## Route
- Namespace: `bilibili`
- Namespace Name: `哔哩哔哩 bilibili`
- Route Path: `/video/danmaku/:bvid/:pid?`
- Route Name: `视频弹幕`
- Example: `/bilibili/video/danmaku/BV1vA411b7ip/1`
- URL: `www.bilibili.com`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `Qixingchen`
- Source Location: `danmaku.ts`
- Source Module: `() => import('@/routes/bilibili/danmaku.ts')`

## Description
_None_

## Parameters
- `bvid`: 视频AV号,可在视频页 URL 中找到
- `pid`: 分P号,不填默认为1


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
  "example": "/bilibili/video/danmaku/BV1vA411b7ip/1",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "danmaku.ts",
  "maintainers": [
    "Qixingchen"
  ],
  "module": "() => import('@/routes/bilibili/danmaku.ts')",
  "name": "视频弹幕",
  "parameters": {
    "bvid": "视频AV号,可在视频页 URL 中找到",
    "pid": "分P号,不填默认为1"
  },
  "path": "/video/danmaku/:bvid/:pid?"
}
```
