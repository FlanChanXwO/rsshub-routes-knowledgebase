# Dribbble - Popular

## Coverage
`index-only`

## Route
- Namespace: `dribbble`
- Namespace Name: `Dribbble`
- Route Path: `/popular/:timeframe?`
- Route Name: `Popular`
- Example: `/dribbble/popular`
- URL: `dribbble.com/`
- Language: `en`
- Categories: `design`
- Maintainers: `DIYgod, loganrockmore`
- Source Location: `popular.ts`
- Source Module: `() => import('@/routes/dribbble/popular.ts')`

## Description
_None_

## Parameters
- `timeframe`: support the following values: week, month, year and ever


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
  - `dribbble.com/`
- `target`: `/popular`

## Raw JSON
```json
{
  "categories": [
    "design"
  ],
  "example": "/dribbble/popular",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "popular.ts",
  "maintainers": [
    "DIYgod",
    "loganrockmore"
  ],
  "module": "() => import('@/routes/dribbble/popular.ts')",
  "name": "Popular",
  "parameters": {
    "timeframe": "support the following values: week, month, year and ever"
  },
  "path": "/popular/:timeframe?",
  "radar": [
    {
      "source": [
        "dribbble.com/"
      ],
      "target": "/popular"
    }
  ],
  "url": "dribbble.com/"
}
```
