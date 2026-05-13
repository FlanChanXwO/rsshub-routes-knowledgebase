# APKPure - Versions

## Coverage
`index-only`

## Route
- Namespace: `apkpure`
- Namespace Name: `APKPure`
- Route Path: `/versions/:pkg/:region?`
- Route Name: `Versions`
- Example: `/apkpure/versions/jp.co.craftegg.band/jp`
- URL: `apkpure.com`
- Language: `en`
- Categories: `program-update`
- Maintainers: `maple3142`
- Source Location: `versions.ts`
- Source Module: `() => import('@/routes/apkpure/versions.ts')`

## Description
_None_

## Parameters
- `pkg`: Package name
- `region`: Region code, `en` by default


## Features
- `requireConfig`: false
- `requirePuppeteer`: true
- `antiCrawler`: true
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
  "example": "/apkpure/versions/jp.co.craftegg.band/jp",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "versions.ts",
  "maintainers": [
    "maple3142"
  ],
  "module": "() => import('@/routes/apkpure/versions.ts')",
  "name": "Versions",
  "parameters": {
    "pkg": "Package name",
    "region": "Region code, `en` by default"
  },
  "path": "/versions/:pkg/:region?"
}
```
