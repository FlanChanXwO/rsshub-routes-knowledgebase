# Polymarket - User Positions

## Coverage
`index-only`

## Route
- Namespace: `polymarket`
- Namespace Name: `Polymarket`
- Route Path: `/positions/:address`
- Route Name: `User Positions`
- Example: `/polymarket/positions/0x7c3db723f1d4d8cb9c550095203b686cb11e5c6b`
- URL: `polymarket.com`
- Language: `en`
- Categories: `finance`
- Maintainers: `heqi201255`
- Source Location: `positions.ts`
- Source Module: `() => import('@/routes/polymarket/positions.ts')`

## Description
_None_

## Parameters
- `address`: Wallet address (0x...)


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
    "finance"
  ],
  "example": "/polymarket/positions/0x7c3db723f1d4d8cb9c550095203b686cb11e5c6b",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "positions.ts",
  "maintainers": [
    "heqi201255"
  ],
  "module": "() => import('@/routes/polymarket/positions.ts')",
  "name": "User Positions",
  "parameters": {
    "address": "Wallet address (0x...)"
  },
  "path": "/positions/:address",
  "url": "polymarket.com"
}
```
