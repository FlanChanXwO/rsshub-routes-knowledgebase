# Followin - KOL

## Coverage
`index-only`

## Route
- Namespace: `followin`
- Namespace Name: `Followin`
- Route Path: `/kol/:kolId/:lang?`
- Route Name: `KOL`
- Example: `/followin/kol/4075592991`
- URL: `followin.io`
- Language: `zh-CN`
- Categories: `finance`
- Maintainers: `TonyRL`
- Source Location: `kol.ts`
- Source Module: `() => import('@/routes/followin/kol.ts')`

## Description
_None_

## Parameters
- `kolId`: KOL ID, can be found in URL
- `lang`: Language, see table above, `en` by default


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
  - `followin.io/:lang/kol/:kolId`
  - `followin.io/kol/:kolId`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/followin/kol/4075592991",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "kol.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/followin/kol.ts')",
  "name": "KOL",
  "parameters": {
    "kolId": "KOL ID, can be found in URL",
    "lang": "Language, see table above, `en` by default"
  },
  "path": "/kol/:kolId/:lang?",
  "radar": [
    {
      "source": [
        "followin.io/:lang/kol/:kolId",
        "followin.io/kol/:kolId"
      ]
    }
  ]
}
```
