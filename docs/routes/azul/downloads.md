# Azul - Downloads

## Coverage
`index-only`

## Route
- Namespace: `azul`
- Namespace Name: `Azul`
- Route Path: `/downloads`
- Route Name: `Downloads`
- Example: `/azul/downloads`
- URL: `www.azul.com`
- Language: `en`
- Categories: `program-update`
- Maintainers: `nczitzk`
- Source Location: `packages.ts`
- Source Module: `() => import('@/routes/azul/packages.ts')`

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
  - `www.azul.com/downloads`
- `target`: `/downloads`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "example": "/azul/downloads",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "packages.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/azul/packages.ts')",
  "name": "Downloads",
  "path": "/downloads",
  "radar": [
    {
      "source": [
        "www.azul.com/downloads"
      ],
      "target": "/downloads"
    }
  ],
  "url": "www.azul.com",
  "view": 5
}
```
