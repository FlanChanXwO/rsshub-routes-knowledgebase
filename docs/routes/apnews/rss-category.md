# AP News - News

## Coverage
`index-only`

## Route
- Namespace: `apnews`
- Namespace Name: `AP News`
- Route Path: `/rss/:category?`
- Route Name: `News`
- Example: `/apnews/rss/business`
- URL: `apnews.com`
- Language: `en`
- Categories: `traditional-media`
- Maintainers: `zoenglinghou, mjysci, TonyRL`
- Source Location: `rss.ts`
- Source Module: `() => import('@/routes/apnews/rss.ts')`

## Description
_None_

## Parameters
- `category`: {"default": "index", "description": "Category from the first segment of the corresponding site, or `index` for the front page."}


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
  - `apnews.com/:rss`
- `target`: `/rss/:rss`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/apnews/rss/business",
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
    "zoenglinghou",
    "mjysci",
    "TonyRL"
  ],
  "module": "() => import('@/routes/apnews/rss.ts')",
  "name": "News",
  "parameters": {
    "category": {
      "default": "index",
      "description": "Category from the first segment of the corresponding site, or `index` for the front page."
    }
  },
  "path": "/rss/:category?",
  "radar": [
    {
      "source": [
        "apnews.com/:rss"
      ],
      "target": "/rss/:rss"
    }
  ],
  "view": 0
}
```
