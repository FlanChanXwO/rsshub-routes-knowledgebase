# 数字尾巴 - 视频

## Coverage
`index-only`

## Route
- Namespace: `dgtle`
- Namespace Name: `数字尾巴`
- Route Path: `/video`
- Route Name: `视频`
- Example: `/dgtle/video`
- URL: `www.dgtle.com`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `video.ts`
- Source Module: `() => import('@/routes/dgtle/video.ts')`

## Description
_None_

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.dgtle.com/video`
- `target`: `/video`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/dgtle/video",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "video.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/dgtle/video.ts')",
  "name": "视频",
  "path": "/video",
  "radar": [
    {
      "source": [
        "www.dgtle.com/video"
      ],
      "target": "/video"
    }
  ],
  "url": "www.dgtle.com",
  "view": 0
}
```
