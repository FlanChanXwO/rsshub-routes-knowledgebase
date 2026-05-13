# Microsoft - Addons Update

## Coverage
`index-only`

## Route
- Namespace: `microsoft`
- Namespace Name: `Microsoft`
- Route Path: `/edge/addon/:crxid`
- Route Name: `Addons Update`
- Example: `/microsoft/edge/addon/gangkeiaobmjcjokiofpkfpcobpbmnln`
- URL: `microsoft.com`
- Language: `en`
- Categories: `program-update`
- Maintainers: `hoilc, DIYgod`
- Source Location: `addon.ts`
- Source Module: `() => import('@/routes/microsoft/addon.ts')`

## Description
_None_

## Parameters
- `crxid`: Addon id, can be found in addon url


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
  - `microsoftedge.microsoft.com/addons/detail/:name/:crxid`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "example": "/microsoft/edge/addon/gangkeiaobmjcjokiofpkfpcobpbmnln",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "addon.ts",
  "maintainers": [
    "hoilc",
    "DIYgod"
  ],
  "module": "() => import('@/routes/microsoft/addon.ts')",
  "name": "Addons Update",
  "parameters": {
    "crxid": "Addon id, can be found in addon url"
  },
  "path": "/edge/addon/:crxid",
  "radar": [
    {
      "source": [
        "microsoftedge.microsoft.com/addons/detail/:name/:crxid"
      ]
    }
  ]
}
```
