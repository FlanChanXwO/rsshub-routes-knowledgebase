# 腾讯网 - 全民K歌 - 用户作品评论动态

## Coverage
`index-only`

## Route
- Namespace: `qq`
- Namespace Name: `腾讯网`
- Route Path: `/kg/reply/:playId`
- Route Name: `全民K歌 - 用户作品评论动态`
- Example: `/qq/kg/reply/OhXHMdO1VxLWQOOm`
- URL: `qq.com`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `zhangxiang012`
- Source Location: `kg/reply.ts`
- Source Module: `() => import('@/routes/qq/kg/reply.ts')`

## Description
_None_

## Parameters
- `playId`: 音频页 ID, 可在对应页面的 URL 中找到


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
  "example": "/qq/kg/reply/OhXHMdO1VxLWQOOm",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "kg/reply.ts",
  "maintainers": [
    "zhangxiang012"
  ],
  "module": "() => import('@/routes/qq/kg/reply.ts')",
  "name": "全民K歌 - 用户作品评论动态",
  "parameters": {
    "playId": "音频页 ID, 可在对应页面的 URL 中找到"
  },
  "path": "/kg/reply/:playId"
}
```
