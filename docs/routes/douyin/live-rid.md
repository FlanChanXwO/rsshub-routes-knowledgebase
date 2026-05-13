# 抖音直播 - 直播间开播

## Coverage
`index-only`

## Route
- Namespace: `douyin`
- Namespace Name: `抖音直播`
- Route Path: `/live/:rid`
- Route Name: `直播间开播`
- Example: `/douyin/live/685317364746`
- URL: `douyin.com`
- Language: `zh-CN`
- Categories: `live`
- Maintainers: `TonyRL`
- Source Location: `live.ts`
- Source Module: `() => import('@/routes/douyin/live.ts')`

## Description
_None_

## Parameters
- `rid`: 直播间 id, 可在主播直播间页 URL 中找到


## Features
- `requireConfig`: false
- `requirePuppeteer`: true
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `live.douyin.com/:rid`

## Raw JSON
```json
{
  "categories": [
    "live"
  ],
  "example": "/douyin/live/685317364746",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "live.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/douyin/live.ts')",
  "name": "直播间开播",
  "parameters": {
    "rid": "直播间 id, 可在主播直播间页 URL 中找到"
  },
  "path": "/live/:rid",
  "radar": [
    {
      "source": [
        "live.douyin.com/:rid"
      ]
    }
  ]
}
```
