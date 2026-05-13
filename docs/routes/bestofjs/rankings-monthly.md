# Best of JS - Monthly Rankings

## Coverage
`index-only`

## Route
- Namespace: `bestofjs`
- Namespace Name: `Best of JS`
- Route Path: `/rankings/monthly`
- Route Name: `Monthly Rankings`
- Example: `/bestofjs/rankings/monthly`
- URL: `bestofjs.org/rankings/monthly`
- Language: `en`
- Categories: `programming`
- Maintainers: `ztkuaikuai`
- Source Location: `monthly.tsx`
- Source Module: `() => import('@/routes/bestofjs/monthly.tsx')`

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
  - `bestofjs.org/rankings/monthly/:year/:month`
- `target`: `/rankings/monthly`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/bestofjs/rankings/monthly",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "monthly.tsx",
  "maintainers": [
    "ztkuaikuai"
  ],
  "module": "() => import('@/routes/bestofjs/monthly.tsx')",
  "name": "Monthly Rankings",
  "path": "/rankings/monthly",
  "radar": [
    {
      "source": [
        "bestofjs.org/rankings/monthly/:year/:month"
      ],
      "target": "/rankings/monthly"
    }
  ],
  "url": "bestofjs.org/rankings/monthly",
  "view": 5
}
```
