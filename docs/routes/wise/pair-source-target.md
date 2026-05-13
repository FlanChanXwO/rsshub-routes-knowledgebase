# Wise - FX Pair Yesterday

## Coverage
`index-only`

## Route
- Namespace: `wise`
- Namespace Name: `Wise`
- Route Path: `/pair/:source/:target`
- Route Name: `FX Pair Yesterday`
- Example: `/wise/pair/GBP/USD`
- URL: `wise.com`
- Language: `en`
- Categories: `other`
- Maintainers: `HenryQW`
- Source Location: `pair.tsx`
- Source Module: `() => import('@/routes/wise/pair.tsx')`

## Description
Refer to [the list of supported currencies](https://wise.com/tools/exchange-rate-alerts/).

## Parameters
- `source`: Base currency abbreviation
- `target`: Quote currency abbreviation


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
  "description": "Refer to [the list of supported currencies](https://wise.com/tools/exchange-rate-alerts/).",
  "example": "/wise/pair/GBP/USD",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "pair.tsx",
  "maintainers": [
    "HenryQW"
  ],
  "module": "() => import('@/routes/wise/pair.tsx')",
  "name": "FX Pair Yesterday",
  "parameters": {
    "source": "Base currency abbreviation",
    "target": "Quote currency abbreviation"
  },
  "path": "/pair/:source/:target"
}
```
