# The New York Times - News

## Coverage
`index-only`

## Route
- Namespace: `nytimes`
- Namespace Name: `The New York Times`
- Route Path: `/rss/:cat?`
- Route Name: `News`
- Example: `/nytimes/rss/HomePage`
- URL: `nytimes.com/`
- Language: `en`
- Categories: `traditional-media`
- Maintainers: `HenryQW, pseudoyu, dzx-dzx`
- Source Location: `rss.ts`
- Source Module: `() => import('@/routes/nytimes/rss.ts')`

## Description
Enhance the official EN RSS feed

## Parameters
- `cat`: {"description": "Category name, corresponding to the last segment of [official feed's](https://www.nytimes.com/rss) url."}


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
  - `nytimes.com/`
- `target`: ``

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "Enhance the official EN RSS feed",
  "example": "/nytimes/rss/HomePage",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "rss.ts",
  "maintainers": [
    "HenryQW",
    "pseudoyu",
    "dzx-dzx"
  ],
  "module": "() => import('@/routes/nytimes/rss.ts')",
  "name": "News",
  "parameters": {
    "cat": {
      "description": "Category name, corresponding to the last segment of [official feed's](https://www.nytimes.com/rss) url."
    }
  },
  "path": "/rss/:cat?",
  "radar": [
    {
      "source": [
        "nytimes.com/"
      ],
      "target": ""
    }
  ],
  "url": "nytimes.com/",
  "view": 0
}
```
