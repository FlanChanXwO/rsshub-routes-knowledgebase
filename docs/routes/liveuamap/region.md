# Live Universal Awareness Map - 实时消息

## Coverage
`index-only`

## Route
- Namespace: `liveuamap`
- Namespace Name: `Live Universal Awareness Map`
- Route Path: `/:region?`
- Route Name: `实时消息`
- Example: `/liveuamap`
- URL: `liveuamap.com`
- Language: `en`
- Categories: `new-media`
- Maintainers: `CoderSherlock`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/liveuamap/index.ts')`

## Description
_None_

## Parameters
- `region`: region 热点地区，默认为`ukraine`，其他选项见liveuamap.com的三级域名


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
  - `liveuamap.com/:region*`
- `target`: `/:region`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/liveuamap",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.ts",
  "maintainers": [
    "CoderSherlock"
  ],
  "module": "() => import('@/routes/liveuamap/index.ts')",
  "name": "实时消息",
  "parameters": {
    "region": "region 热点地区，默认为`ukraine`，其他选项见liveuamap.com的三级域名"
  },
  "path": "/:region?",
  "radar": [
    {
      "source": [
        "liveuamap.com/:region*"
      ],
      "target": "/:region"
    }
  ]
}
```
