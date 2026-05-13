# App Store/Mac App Store - Price Drop

## Coverage
`index-only`

## Route
- Namespace: `appstore`
- Namespace Name: `App Store/Mac App Store`
- Route Path: `/price/:country/:type/:id`
- Route Name: `Price Drop`
- Example: `/appstore/price/us/mac/id1152443474`
- URL: `apps.apple.com/`
- Language: `en`
- Categories: `program-update`
- Maintainers: `HenryQW`
- Source Location: `price.ts`
- Source Module: `() => import('@/routes/appstore/price.ts')`

## Description
_None_

## Parameters
- `country`: App Store Country, obtain from the app URL https://apps.apple.com/us/app/id1152443474, in this case, `us`
- `type`: App type，either `iOS` or `mac`
- `id`: App Store app id, obtain from the app URL https://apps.apple.com/us/app/id1152443474, in this case, `id1152443474`


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
  - `apps.apple.com/`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "example": "/appstore/price/us/mac/id1152443474",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "price.ts",
  "maintainers": [
    "HenryQW"
  ],
  "module": "() => import('@/routes/appstore/price.ts')",
  "name": "Price Drop",
  "parameters": {
    "country": "App Store Country, obtain from the app URL https://apps.apple.com/us/app/id1152443474, in this case, `us`",
    "id": "App Store app id, obtain from the app URL https://apps.apple.com/us/app/id1152443474, in this case, `id1152443474`",
    "type": "App type，either `iOS` or `mac`"
  },
  "path": "/price/:country/:type/:id",
  "radar": [
    {
      "source": [
        "apps.apple.com/"
      ]
    }
  ],
  "url": "apps.apple.com/"
}
```
