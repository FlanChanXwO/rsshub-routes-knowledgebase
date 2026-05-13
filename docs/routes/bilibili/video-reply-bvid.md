# 哔哩哔哩 bilibili - 视频评论

## Coverage
`index-only`

## Route
- Namespace: `bilibili`
- Namespace Name: `哔哩哔哩 bilibili`
- Route Path: `/video/reply/:bvid`
- Route Name: `视频评论`
- Example: `/bilibili/video/reply/BV1vA411b7ip`
- URL: `www.bilibili.com`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `Qixingchen`
- Source Location: `reply.ts`
- Source Module: `() => import('@/routes/bilibili/reply.ts')`

## Description
_None_

## Parameters
- `bvid`: 可在视频页 URL 中找到


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
  "example": "/bilibili/video/reply/BV1vA411b7ip",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "reply.ts",
  "maintainers": [
    "Qixingchen"
  ],
  "module": "() => import('@/routes/bilibili/reply.ts')",
  "name": "视频评论",
  "parameters": {
    "bvid": "可在视频页 URL 中找到"
  },
  "path": "/video/reply/:bvid"
}
```
