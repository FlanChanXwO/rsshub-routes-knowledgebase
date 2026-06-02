# Live Universal Awareness Map - 实时消息

## Coverage
`index-only`

## Route
- Namespace: `liveuamap`
- Namespace Name: `Live Universal Awareness Map`
- Route Path: `/liveuamap/:region?`
- Route Name: `实时消息`
- Example: `/liveuamap`
- URL: `liveuamap.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `CoderSherlock`
- Source Location: `index.ts`
- Source Module: `_None_`

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
  "heat": 67,
  "location": "index.ts",
  "maintainers": [
    "CoderSherlock"
  ],
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
  ],
  "topFeeds": [
    {
      "description": "Liveuamap - ukraine - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "59767594613902336",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://ukraine.liveuamap.com/",
      "title": "Liveuamap - ukraine",
      "type": "feed",
      "url": "rsshub://liveuamap"
    },
    {
      "description": "Liveuamap - china - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "85175414937704448",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://china.liveuamap.com/",
      "title": "Liveuamap - china",
      "type": "feed",
      "url": "rsshub://liveuamap/china"
    }
  ]
}
```
