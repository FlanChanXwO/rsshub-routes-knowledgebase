# CNBC - Full article RSS

## Coverage
`index-only`

## Route
- Namespace: `cnbc`
- Namespace Name: `CNBC`
- Route Path: `/rss/:id?`
- Route Name: `Full article RSS`
- Example: `/cnbc/rss`
- URL: `search.cnbc.com`
- Language: `en`
- Categories: `traditional-media`
- Maintainers: `TonyRL`
- Source Location: `rss.ts`
- Source Module: `() => import('@/routes/cnbc/rss.ts')`

## Description
Provides a better reading experience (full articles) over the official ones.

  Support all channels, refer to [CNBC RSS feeds](https://www.cnbc.com/rss-feeds/).

## Parameters
- `id`: Channel ID, can be found in Official RSS URL, `100003114` (Top News) by default


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
  - `www.cnbc.com/id/:id/device/rss/rss.html`
- `target`: `/rss/:id`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "Provides a better reading experience (full articles) over the official ones.\n\n  Support all channels, refer to [CNBC RSS feeds](https://www.cnbc.com/rss-feeds/).",
  "example": "/cnbc/rss",
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
    "TonyRL"
  ],
  "module": "() => import('@/routes/cnbc/rss.ts')",
  "name": "Full article RSS",
  "parameters": {
    "id": "Channel ID, can be found in Official RSS URL, `100003114` (Top News) by default"
  },
  "path": "/rss/:id?",
  "radar": [
    {
      "source": [
        "www.cnbc.com/id/:id/device/rss/rss.html"
      ],
      "target": "/rss/:id"
    }
  ]
}
```
