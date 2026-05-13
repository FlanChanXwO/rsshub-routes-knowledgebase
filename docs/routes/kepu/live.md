# 中国科普博览 - 直播回看

## Coverage
`index-only`

## Route
- Namespace: `kepu`
- Namespace Name: `中国科普博览`
- Route Path: `/live`
- Route Name: `直播回看`
- Example: `/kepu/live`
- URL: `live.kepu.net.cn/replay/index`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `live.tsx`
- Source Module: `() => import('@/routes/kepu/live.tsx')`

## Description
_None_

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: true
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `live.kepu.net.cn/replay/index`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/kepu/live",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": true,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "live.tsx",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/kepu/live.tsx')",
  "name": "直播回看",
  "parameters": {},
  "path": "/live",
  "radar": [
    {
      "source": [
        "live.kepu.net.cn/replay/index"
      ]
    }
  ],
  "url": "live.kepu.net.cn/replay/index"
}
```
