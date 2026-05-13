# App Store/Mac App Store - In-App-Purchase Price Drop Alert

## Coverage
`index-only`

## Route
- Namespace: `appstore`
- Namespace Name: `App Store/Mac App Store`
- Route Path: `/iap/:country/:id`
- Route Name: `In-App-Purchase Price Drop Alert`
- Example: `/appstore/iap/us/id953286746`
- URL: `apps.apple.com`
- Language: `en`
- Categories: `program-update`
- Maintainers: `HenryQW`
- Source Location: `in-app-purchase.ts`
- Source Module: `() => import('@/routes/appstore/in-app-purchase.ts')`

## Description
_None_

## Parameters
- `country`: App Store Country, obtain from the app URL https://apps.apple.com/us/app/id953286746, in this case, `us`
- `id`: App Store app id, obtain from the app URL https://apps.apple.com/us/app/id953286746, in this case, `id953286746`


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "example": "/appstore/iap/us/id953286746",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "in-app-purchase.ts",
  "maintainers": [
    "HenryQW"
  ],
  "module": "() => import('@/routes/appstore/in-app-purchase.ts')",
  "name": "In-App-Purchase Price Drop Alert",
  "parameters": {
    "country": "App Store Country, obtain from the app URL https://apps.apple.com/us/app/id953286746, in this case, `us`",
    "id": "App Store app id, obtain from the app URL https://apps.apple.com/us/app/id953286746, in this case, `id953286746`"
  },
  "path": "/iap/:country/:id"
}
```
