# The Australian Financial Review - Latest

## Coverage
`index-only`

## Route
- Namespace: `afr`
- Namespace Name: `The Australian Financial Review`
- Route Path: `/latest`
- Route Name: `Latest`
- Example: `/afr/latest`
- URL: `www.afr.com/latest`
- Language: `en`
- Categories: `traditional-media`
- Maintainers: `TonyRL`
- Source Location: `latest.ts`
- Source Module: `() => import('@/routes/afr/latest.ts')`

## Description
_None_

## Parameters
_None_


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
  - `www.afr.com/latest`
  - `www.afr.com/`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/afr/latest",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "latest.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/afr/latest.ts')",
  "name": "Latest",
  "path": "/latest",
  "radar": [
    {
      "source": [
        "www.afr.com/latest",
        "www.afr.com/"
      ]
    }
  ],
  "url": "www.afr.com/latest"
}
```
