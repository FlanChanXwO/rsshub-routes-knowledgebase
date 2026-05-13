# Apple - Exchange and Repair Extension Programs

## Coverage
`index-only`

## Route
- Namespace: `apple`
- Namespace Name: `Apple`
- Route Path: `/exchange_repair/:country?`
- Route Name: `Exchange and Repair Extension Programs`
- Example: `/apple/exchange_repair`
- URL: `apple.com`
- Language: `en`
- Categories: `other`
- Maintainers: `metowolf, HenryQW, kt286`
- Source Location: `exchange-repair.ts`
- Source Module: `() => import('@/routes/apple/exchange-repair.ts')`

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
  "location": "exchange-repair.ts",
  "maintainers": [
    "metowolf",
    "HenryQW",
    "kt286"
  ],
  "module": "() => import('@/routes/apple/exchange-repair.ts')",
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
  ]
}
```
