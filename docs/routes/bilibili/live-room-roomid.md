# 哔哩哔哩 bilibili - 直播开播

## Coverage
`index-only`

## Route
- Namespace: `bilibili`
- Namespace Name: `哔哩哔哩 bilibili`
- Route Path: `/live/room/:roomID`
- Route Name: `直播开播`
- Example: `/bilibili/live/room/3`
- URL: `www.bilibili.com`
- Language: `zh-CN`
- Categories: `live`
- Maintainers: `Qixingchen`
- Source Location: `live-room.ts`
- Source Module: `() => import('@/routes/bilibili/live-room.ts')`

## Description
_None_

## Parameters
- `roomID`: 房间号, 可在直播间 URL 中找到, 长短号均可


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
  - `live.bilibili.com/:roomID`

## Raw JSON
```json
{
  "categories": [
    "live"
  ],
  "example": "/bilibili/live/room/3",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "live-room.ts",
  "maintainers": [
    "Qixingchen"
  ],
  "module": "() => import('@/routes/bilibili/live-room.ts')",
  "name": "直播开播",
  "parameters": {
    "roomID": "房间号, 可在直播间 URL 中找到, 长短号均可"
  },
  "path": "/live/room/:roomID",
  "radar": [
    {
      "source": [
        "live.bilibili.com/:roomID"
      ]
    }
  ]
}
```
