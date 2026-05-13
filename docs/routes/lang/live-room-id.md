# 浪 Play 直播 - 直播间开播

## Coverage
`index-only`

## Route
- Namespace: `lang`
- Namespace Name: `浪 Play 直播`
- Route Path: `/live/room/:id`
- Route Name: `直播间开播`
- Example: `/lang/live/room/1352360`
- URL: `lang.live`
- Language: `zh-CN`
- Categories: `live`
- Maintainers: `MittWillson`
- Source Location: `room.tsx`
- Source Module: `() => import('@/routes/lang/room.tsx')`

## Description
_None_

## Parameters
- `id`: 直播间 id, 可在主播直播间页 URL 中找到


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `lang.live/room/:id`

## Raw JSON
```json
{
  "categories": [
    "live"
  ],
  "example": "/lang/live/room/1352360",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "room.tsx",
  "maintainers": [
    "MittWillson"
  ],
  "module": "() => import('@/routes/lang/room.tsx')",
  "name": "直播间开播",
  "parameters": {
    "id": "直播间 id, 可在主播直播间页 URL 中找到"
  },
  "path": "/live/room/:id",
  "radar": [
    {
      "source": [
        "lang.live/room/:id"
      ]
    }
  ]
}
```
