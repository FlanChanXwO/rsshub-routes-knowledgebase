# Polymarket - Events

## Coverage
`index-only`

## Route
- Namespace: `polymarket`
- Namespace Name: `Polymarket`
- Route Path: `/events/:tagSlug?`
- Route Name: `Events`
- Example: `/polymarket/events`
- URL: `polymarket.com`
- Language: `en`
- Categories: `finance`
- Maintainers: `heqi201255`
- Source Location: `events.ts`
- Source Module: `() => import('@/routes/polymarket/events.ts')`

## Description
_None_

## Parameters
- `tagSlug`: Tag slug to filter events, e.g. politics, sports, crypto. Omit for all events.


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
  - `polymarket.com`
  - `polymarket.com/:tagSlug`
- `target`: `/events/:tagSlug`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/polymarket/events",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "events.ts",
  "maintainers": [
    "heqi201255"
  ],
  "module": "() => import('@/routes/polymarket/events.ts')",
  "name": "Events",
  "parameters": {
    "tagSlug": "Tag slug to filter events, e.g. politics, sports, crypto. Omit for all events."
  },
  "path": "/events/:tagSlug?",
  "radar": [
    {
      "source": [
        "polymarket.com",
        "polymarket.com/:tagSlug"
      ],
      "target": "/events/:tagSlug"
    }
  ],
  "url": "polymarket.com"
}
```
