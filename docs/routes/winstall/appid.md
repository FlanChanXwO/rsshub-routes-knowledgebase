# winstall - Apps Update

## Coverage
`index-only`

## Route
- Namespace: `winstall`
- Namespace Name: `winstall`
- Route Path: `/:appId`
- Route Name: `Apps Update`
- Example: `/winstall/Mozilla.Firefox`
- URL: `winstall.app`
- Language: `en`
- Categories: `program-update`
- Maintainers: `TonyRL`
- Source Location: `update.tsx`
- Source Module: `() => import('@/routes/winstall/update.tsx')`

## Description
_None_

## Parameters
- `appId`: Application ID


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
  - `winstall.app/apps/:appId`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "example": "/winstall/Mozilla.Firefox",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "update.tsx",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/winstall/update.tsx')",
  "name": "Apps Update",
  "parameters": {
    "appId": "Application ID"
  },
  "path": "/:appId",
  "radar": [
    {
      "source": [
        "winstall.app/apps/:appId"
      ]
    }
  ]
}
```
