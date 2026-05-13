# F-Droid - App Update

## Coverage
`index-only`

## Route
- Namespace: `f-droid`
- Namespace Name: `F-Droid`
- Route Path: `/apprelease/:app`
- Route Name: `App Update`
- Example: `/f-droid/apprelease/com.termux`
- URL: `f-droid.org`
- Language: `zh-CN`
- Categories: `program-update`
- Maintainers: `garywill`
- Source Location: `apprelease.ts`
- Source Module: `() => import('@/routes/f-droid/apprelease.ts')`

## Description
_None_

## Parameters
- `app`: App's package name


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
  - `f-droid.org/en/packages/:app/`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "example": "/f-droid/apprelease/com.termux",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "apprelease.ts",
  "maintainers": [
    "garywill"
  ],
  "module": "() => import('@/routes/f-droid/apprelease.ts')",
  "name": "App Update",
  "parameters": {
    "app": "App's package name"
  },
  "path": "/apprelease/:app",
  "radar": [
    {
      "source": [
        "f-droid.org/en/packages/:app/"
      ]
    }
  ]
}
```
