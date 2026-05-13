# Epic Games Store - Free games

## Coverage
`index-only`

## Route
- Namespace: `epicgames`
- Namespace Name: `Epic Games Store`
- Route Path: `/freegames/:locale?/:country?`
- Route Name: `Free games`
- Example: `/epicgames/freegames/en-US/US`
- URL: `store.epicgames.com`
- Language: `en`
- Categories: `game`
- Maintainers: `DIYgod, NeverBehave, Zyx-A, junfengP, nczitzk, KotaHv`
- Source Location: `index.tsx`
- Source Module: `() => import('@/routes/epicgames/index.tsx')`

## Description
_None_

## Parameters
- `locale`: {"default": "en-US", "description": "Locale"}
- `country`: {"default": "US", "description": "Country"}


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
  - `store.epicgames.com/:locale/free-games`
- `target`: `/freegames/:locale`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "example": "/epicgames/freegames/en-US/US",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.tsx",
  "maintainers": [
    "DIYgod",
    "NeverBehave",
    "Zyx-A",
    "junfengP",
    "nczitzk",
    "KotaHv"
  ],
  "module": "() => import('@/routes/epicgames/index.tsx')",
  "name": "Free games",
  "parameters": {
    "country": {
      "default": "US",
      "description": "Country"
    },
    "locale": {
      "default": "en-US",
      "description": "Locale"
    }
  },
  "path": "/freegames/:locale?/:country?",
  "radar": [
    {
      "source": [
        "store.epicgames.com/:locale/free-games"
      ],
      "target": "/freegames/:locale"
    }
  ],
  "view": 5
}
```
