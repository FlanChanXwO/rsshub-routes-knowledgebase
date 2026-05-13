# 斗鱼直播 - 直播间开播

## Coverage
`index-only`

## Route
- Namespace: `douyu`
- Namespace Name: `斗鱼直播`
- Route Path: `/room/:id`
- Route Name: `直播间开播`
- Example: `/douyu/room/24422`
- URL: `www.douyu.com`
- Language: `zh-CN`
- Categories: `live`
- Maintainers: `DIYgod, ChaosTong`
- Source Location: `room.ts`
- Source Module: `() => import('@/routes/douyu/room.ts')`

## Description
_None_

## Parameters
- `id`: 直播间 id, 可在主播直播间页 URL 中找到


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
  - `www.douyu.com/:id`
  - `www.douyu.com/`

## Raw JSON
```json
{
  "categories": [
    "live"
  ],
  "example": "/douyu/room/24422",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "room.ts",
  "maintainers": [
    "DIYgod",
    "ChaosTong"
  ],
  "module": "() => import('@/routes/douyu/room.ts')",
  "name": "直播间开播",
  "parameters": {
    "id": "直播间 id, 可在主播直播间页 URL 中找到"
  },
  "path": "/room/:id",
  "radar": [
    {
      "source": [
        "www.douyu.com/:id",
        "www.douyu.com/"
      ]
    }
  ]
}
```
