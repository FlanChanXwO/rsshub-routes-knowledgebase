# 浪 Play 直播 - 直播间开播

## Coverage
`index-only`

## Route
- Namespace: `lang`
- Namespace Name: `浪 Play 直播`
- Route Path: `/lang/live/room/:id`
- Route Name: `直播间开播`
- Example: `/lang/live/room/1352360`
- URL: `lang.live`
- Language: `_None_`
- Categories: `live`
- Maintainers: `MittWillson`
- Source Location: `room.tsx`
- Source Module: `_None_`

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
  "heat": 56,
  "location": "room.tsx",
  "maintainers": [
    "MittWillson"
  ],
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
  ],
  "topFeeds": [
    {
      "description": "总有些惊奇的际遇，比方说当我遇见你。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "154544860488526848",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.lang.live/room/1352360",
      "title": "🌶穩住！小辣椒～🦖 的浪 Play 直播",
      "type": "feed",
      "url": "rsshub://lang/live/room/1352360"
    }
  ]
}
```
