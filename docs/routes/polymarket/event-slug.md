# Polymarket - Event

## Coverage
`index-only`

## Route
- Namespace: `polymarket`
- Namespace Name: `Polymarket`
- Route Path: `/event/:slug`
- Route Name: `Event`
- Example: `/polymarket/event/presidential-election-winner-2024`
- URL: `polymarket.com`
- Language: `en`
- Categories: `finance`
- Maintainers: `heqi201255`
- Source Location: `event.ts`
- Source Module: `() => import('@/routes/polymarket/event.ts')`

## Description
_None_

## Parameters
- `slug`: Event slug from the URL (e.g. presidential-election-winner-2024)


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
  - `polymarket.com/event/:slug`
- `target`: `/event/:slug`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/polymarket/event/presidential-election-winner-2024",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "event.ts",
  "maintainers": [
    "heqi201255"
  ],
  "module": "() => import('@/routes/polymarket/event.ts')",
  "name": "Event",
  "parameters": {
    "slug": "Event slug from the URL (e.g. presidential-election-winner-2024)"
  },
  "path": "/event/:slug",
  "radar": [
    {
      "source": [
        "polymarket.com/event/:slug"
      ],
      "target": "/event/:slug"
    }
  ],
  "url": "polymarket.com"
}
```
