# APKPure - Versions

## Coverage
`index-only`

## Route
- Namespace: `apkpure`
- Namespace Name: `APKPure`
- Route Path: `/apkpure/versions/:pkg/:region?`
- Route Name: `Versions`
- Example: `/apkpure/versions/jp.co.craftegg.band/jp`
- URL: `apkpure.com`
- Language: `_None_`
- Categories: `program-update`
- Maintainers: `maple3142`
- Source Location: `versions.ts`
- Source Module: `_None_`

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
  "heat": 0,
  "location": "versions.ts",
  "maintainers": [
    "maple3142"
  ],
  "name": "Versions",
  "parameters": {
    "pkg": "Package name",
    "region": "Region code, `en` by default"
  },
  "path": "/versions/:pkg/:region?",
  "topFeeds": []
}
```
