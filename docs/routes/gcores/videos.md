# 机核网 - 视频

## Coverage
`index-only`

## Route
- Namespace: `gcores`
- Namespace Name: `机核网`
- Route Path: `/videos`
- Route Name: `视频`
- Example: `/gcores/videos`
- URL: `www.gcores.com`
- Language: `zh-CN`
- Categories: `game`
- Maintainers: `nczitzk`
- Source Location: `videos.ts`
- Source Module: `() => import('@/routes/gcores/videos.ts')`

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
  - `www.gcores.com/videos`
- `target`: `/gcores/videos`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "example": "/gcores/videos",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "videos.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/gcores/videos.ts')",
  "name": "视频",
  "path": "/videos",
  "radar": [
    {
      "source": [
        "www.gcores.com/videos"
      ],
      "target": "/gcores/videos"
    }
  ],
  "url": "www.gcores.com",
  "view": 3
}
```
