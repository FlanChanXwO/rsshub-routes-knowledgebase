# UPS - Tracking

## Coverage
`index-only`

## Route
- Namespace: `ups`
- Namespace Name: `UPS`
- Route Path: `/track/:trackingNumber`
- Route Name: `Tracking`
- Example: `/ups/track/1Z78R6790470567520`
- URL: `ups.com`
- Language: `_None_`
- Categories: `other`
- Maintainers: `Aquabet`
- Source Location: `track.ts`
- Source Module: `() => import('@/routes/ups/track.ts')`

## Description
_None_

## Parameters
- `trackingNumber`: The UPS tracking number (e.g., 1Z78R6790470567520).


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "example": "/ups/track/1Z78R6790470567520",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "track.ts",
  "maintainers": [
    "Aquabet"
  ],
  "module": "() => import('@/routes/ups/track.ts')",
  "name": "Tracking",
  "parameters": {
    "trackingNumber": "The UPS tracking number (e.g., 1Z78R6790470567520)."
  },
  "path": "/track/:trackingNumber"
}
```
