# Apple - Exchange and Repair Extension Programs

## Coverage
`index-only`

## Route
- Namespace: `apple`
- Namespace Name: `Apple`
- Route Path: `/apple/exchange_repair/:country?`
- Route Name: `Exchange and Repair Extension Programs`
- Example: `/apple/exchange_repair`
- URL: `apple.com`
- Language: `_None_`
- Categories: `other`
- Maintainers: `metowolf, HenryQW, kt286`
- Source Location: `exchange-repair.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `country`: country code in apple.com URL (exception: for `United States` please use `us`), default to China `cn`


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
  - `support.apple.com/:country/service-programs`
- `target`: `/exchange_repair/:country`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "example": "/apple/exchange_repair",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 24,
  "location": "exchange-repair.ts",
  "maintainers": [
    "metowolf",
    "HenryQW",
    "kt286"
  ],
  "name": "Exchange and Repair Extension Programs",
  "parameters": {
    "country": "country code in apple.com URL (exception: for `United States` please use `us`), default to China `cn`"
  },
  "path": "/exchange_repair/:country?",
  "radar": [
    {
      "source": [
        "support.apple.com/:country/service-programs"
      ],
      "target": "/exchange_repair/:country"
    }
  ],
  "topFeeds": [
    {
      "description": "Apple - Apple 服务计划 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "55178476300040232",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://support.apple.com/zh-cn/service-programs",
      "title": "Apple - Apple 服务计划",
      "type": "feed",
      "url": "rsshub://apple/exchange_repair/zh-cn"
    },
    {
      "description": "Apple - Apple Service Programs - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "63183844748751873",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://support.apple.com/service-programs",
      "title": "Apple - Apple Service Programs",
      "type": "feed",
      "url": "rsshub://apple/exchange_repair"
    }
  ]
}
```
