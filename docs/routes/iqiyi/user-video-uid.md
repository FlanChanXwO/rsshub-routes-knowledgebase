# 爱奇艺 - 用户视频

## Coverage
`index-only`

## Route
- Namespace: `iqiyi`
- Namespace Name: `爱奇艺`
- Route Path: `/user/video/:uid`
- Route Name: `用户视频`
- Example: `/iqiyi/user/video/2289191062`
- URL: `iq.com`
- Language: `zh-CN`
- Categories: `multimedia`
- Maintainers: `talengu, JimenezLi`
- Source Location: `video.ts`
- Source Module: `() => import('@/routes/iqiyi/video.ts')`

## Description
_None_

## Parameters
- `uid`: 用户名


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
  - `iqiyi.com/u/:uid/*`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/iqiyi/user/video/2289191062",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "video.ts",
  "maintainers": [
    "talengu",
    "JimenezLi"
  ],
  "module": "() => import('@/routes/iqiyi/video.ts')",
  "name": "用户视频",
  "parameters": {
    "uid": "用户名"
  },
  "path": "/user/video/:uid",
  "radar": [
    {
      "source": [
        "iqiyi.com/u/:uid/*"
      ]
    }
  ]
}
```
