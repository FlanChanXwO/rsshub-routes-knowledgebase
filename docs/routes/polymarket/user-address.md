# Polymarket - User Activity

## Coverage
`index-only`

## Route
- Namespace: `polymarket`
- Namespace Name: `Polymarket`
- Route Path: `/user/:address`
- Route Name: `User Activity`
- Example: `/polymarket/user/0x7c3db723f1d4d8cb9c550095203b686cb11e5c6b`
- URL: `polymarket.com`
- Language: `en`
- Categories: `finance`
- Maintainers: `heqi201255`
- Source Location: `user.ts`
- Source Module: `() => import('@/routes/polymarket/user.ts')`

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
  "example": "/polymarket/user/0x7c3db723f1d4d8cb9c550095203b686cb11e5c6b",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "user.ts",
  "maintainers": [
    "heqi201255"
  ],
  "module": "() => import('@/routes/polymarket/user.ts')",
  "name": "User Activity",
  "parameters": {
    "address": "Wallet address (0x...)"
  },
  "path": "/user/:address",
  "url": "polymarket.com"
}
```
