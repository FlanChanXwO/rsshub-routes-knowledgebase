# Polymarket - Leaderboard

## Coverage
`index-only`

## Route
- Namespace: `polymarket`
- Namespace Name: `Polymarket`
- Route Path: `/leaderboard/:category?/:timePeriod?`
- Route Name: `Leaderboard`
- Example: `/polymarket/leaderboard`
- URL: `polymarket.com`
- Language: `en`
- Categories: `finance`
- Maintainers: `heqi201255`
- Source Location: `leaderboard.ts`
- Source Module: `() => import('@/routes/polymarket/leaderboard.ts')`

## Description
_None_

## Parameters
- `category`: {"default": "OVERALL", "description": "Market category: OVERALL, POLITICS, SPORTS, CRYPTO, CULTURE, MENTIONS, WEATHER, ECONOMICS, TECH, FINANCE"}
- `timePeriod`: {"default": "DAY", "description": "Time period: DAY, WEEK, MONTH, ALL"}


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
  "example": "/polymarket/leaderboard",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "leaderboard.ts",
  "maintainers": [
    "heqi201255"
  ],
  "module": "() => import('@/routes/polymarket/leaderboard.ts')",
  "name": "Leaderboard",
  "parameters": {
    "category": {
      "default": "OVERALL",
      "description": "Market category: OVERALL, POLITICS, SPORTS, CRYPTO, CULTURE, MENTIONS, WEATHER, ECONOMICS, TECH, FINANCE"
    },
    "timePeriod": {
      "default": "DAY",
      "description": "Time period: DAY, WEEK, MONTH, ALL"
    }
  },
  "path": "/leaderboard/:category?/:timePeriod?",
  "url": "polymarket.com"
}
```
