# Apple - App Update

## Coverage
`index-only`

## Route
- Namespace: `apple`
- Namespace Name: `Apple`
- Route Path: `/apps/update/:country/:id/:platform?`
- Route Name: `App Update`
- Example: `/apple/apps/update/us/id408709785`
- URL: `apple.com`
- Language: `en`
- Categories: `program-update`
- Maintainers: `EkkoG, nczitzk`
- Source Location: `apps.ts`
- Source Module: `() => import('@/routes/apple/apps.ts')`

## Description
::: tip
  For example, the URL of [GarageBand](https://apps.apple.com/us/app/garageband/id408709785) in the App Store is `https://apps.apple.com/us/app/garageband/id408709785`. In this case, the `App Store Country` parameter for the route is `us`, and the `App id` parameter is `id408709785`. So the route should be [`/apple/apps/update/us/id408709785`](https://rsshub.app/apple/apps/update/us/id408709785).
:::

## Parameters
- `country`: App Store Country, obtain from the app URL, see below
- `id`: App id, obtain from the app URL
- `platform`: {"description": "App Platform, see below, all by default", "options": [{"label": "all", "value": "All"}, {"label": "iOS", "value": "iOS"}, {"label": "macOS", "value": "macOS"}, {"label": "tvOS", "value": "tvOS"}]}


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
  - `apps.apple.com/:country/app/:appSlug/:id`
  - `apps.apple.com/:country/app/:id`
- `target`: `/apps/update/:country/:id`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "description": "\n::: tip\n  For example, the URL of [GarageBand](https://apps.apple.com/us/app/garageband/id408709785) in the App Store is `https://apps.apple.com/us/app/garageband/id408709785`. In this case, the `App Store Country` parameter for the route is `us`, and the `App id` parameter is `id408709785`. So the route should be [`/apple/apps/update/us/id408709785`](https://rsshub.app/apple/apps/update/us/id408709785).\n:::",
  "example": "/apple/apps/update/us/id408709785",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "apps.ts",
  "maintainers": [
    "EkkoG",
    "nczitzk"
  ],
  "module": "() => import('@/routes/apple/apps.ts')",
  "name": "App Update",
  "parameters": {
    "country": "App Store Country, obtain from the app URL, see below",
    "id": "App id, obtain from the app URL",
    "platform": {
      "description": "App Platform, see below, all by default",
      "options": [
        {
          "label": "all",
          "value": "All"
        },
        {
          "label": "iOS",
          "value": "iOS"
        },
        {
          "label": "macOS",
          "value": "macOS"
        },
        {
          "label": "tvOS",
          "value": "tvOS"
        }
      ]
    }
  },
  "path": "/apps/update/:country/:id/:platform?",
  "radar": [
    {
      "source": [
        "apps.apple.com/:country/app/:appSlug/:id",
        "apps.apple.com/:country/app/:id"
      ],
      "target": "/apps/update/:country/:id"
    }
  ],
  "view": 5
}
```
