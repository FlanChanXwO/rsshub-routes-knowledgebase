# 腾讯网 - 全民K歌 - 用户作品列表

## Coverage
`index-only`

## Route
- Namespace: `qq`
- Namespace Name: `腾讯网`
- Route Path: `/kg/:userId`
- Route Name: `全民K歌 - 用户作品列表`
- Example: `/qq/kg/639a9a86272c308e33`
- URL: `qq.com`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `zhangxiang012`
- Source Location: `kg/user.ts`
- Source Module: `() => import('@/routes/qq/kg/user.ts')`

## Description
_None_

## Parameters
- `userId`: 用户 ID, 可在对应页面的 URL 中找到


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: true
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/qq/kg/639a9a86272c308e33",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": true,
    "supportScihub": false
  },
  "location": "kg/user.ts",
  "maintainers": [
    "zhangxiang012"
  ],
  "module": "() => import('@/routes/qq/kg/user.ts')",
  "name": "全民K歌 - 用户作品列表",
  "parameters": {
    "userId": "用户 ID, 可在对应页面的 URL 中找到"
  },
  "path": "/kg/:userId"
}
```
