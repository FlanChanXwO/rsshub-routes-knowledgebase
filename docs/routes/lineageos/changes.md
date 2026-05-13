# LineageOS - Changes

## Coverage
`index-only`

## Route
- Namespace: `lineageos`
- Namespace Name: `LineageOS`
- Route Path: `/changes`
- Route Name: `Changes`
- Example: `/lineageos/changes`
- URL: `download.lineageos.org`
- Language: `en`
- Categories: `program-update`
- Maintainers: `nczitzk`
- Source Location: `changes.ts`
- Source Module: `() => import('@/routes/lineageos/changes.ts')`

## Description
_None_

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `download.lineageos.org/changes`
- `target`: `/changes`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "example": "/lineageos/changes",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "changes.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/lineageos/changes.ts')",
  "name": "Changes",
  "path": "/changes",
  "radar": [
    {
      "source": [
        "download.lineageos.org/changes"
      ],
      "target": "/changes"
    }
  ],
  "url": "download.lineageos.org",
  "view": 5
}
```
