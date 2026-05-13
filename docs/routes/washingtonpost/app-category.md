# The Washington Post - App

## Coverage
`index-only`

## Route
- Namespace: `washingtonpost`
- Namespace Name: `The Washington Post`
- Route Path: `/app/:category{.+}?`
- Route Name: `App`
- Example: `/washingtonpost/app/national`
- URL: `www.washingtonpost.com`
- Language: `en`
- Categories: `traditional-media`
- Maintainers: `quiniapiezoelectricity`
- Source Location: `app.tsx`
- Source Module: `() => import('@/routes/washingtonpost/app.tsx')`

## Description
::: tip
For example, the category for https://www.washingtonpost.com/national/investigations would be /national/investigations.
:::

## Parameters
- `category`: Category from the path of the URL of the corresponding site, see below


## Features
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.washingtonpost.com/:category`
- `target`: `/app/:category`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "::: tip\nFor example, the category for https://www.washingtonpost.com/national/investigations would be /national/investigations.\n:::",
  "example": "/washingtonpost/app/national",
  "features": {
    "antiCrawler": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "app.tsx",
  "maintainers": [
    "quiniapiezoelectricity"
  ],
  "module": "() => import('@/routes/washingtonpost/app.tsx')",
  "name": "App",
  "parameters": {
    "category": "Category from the path of the URL of the corresponding site, see below"
  },
  "path": "/app/:category{.+}?",
  "radar": [
    {
      "source": [
        "www.washingtonpost.com/:category"
      ],
      "target": "/app/:category"
    }
  ]
}
```
