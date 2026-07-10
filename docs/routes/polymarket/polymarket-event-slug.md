# Polymarket - Event

## Coverage
`index-only`

## Route
- Namespace: `polymarket`
- Namespace Name: `Polymarket`
- Route Path: `/polymarket/event/:slug`
- Route Name: `Event`
- Example: `/polymarket/event/presidential-election-winner-2024`
- URL: `polymarket.com`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `heqi201255`
- Source Location: `event.ts`
- Source Module: `_None_`

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
  "heat": 0,
  "location": "event.ts",
  "maintainers": [
    "heqi201255"
  ],
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
  "topFeeds": [],
  "url": "polymarket.com"
}
```
