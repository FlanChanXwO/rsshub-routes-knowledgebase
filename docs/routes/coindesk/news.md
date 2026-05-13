# CoinDesk - News

## Coverage
`index-only`

## Route
- Namespace: `coindesk`
- Namespace Name: `CoinDesk`
- Route Path: `/news`
- Route Name: `News`
- Example: `/coindesk/news`
- URL: `coindesk.com`
- Language: `en`
- Categories: `finance`
- Maintainers: `pseudoyu`
- Source Location: `news.ts`
- Source Module: `() => import('@/routes/coindesk/news.ts')`

## Description
Get latest news from CoinDesk with full text.

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
  - `coindesk.com/`
- `target`: `/news`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "Get latest news from CoinDesk with full text.",
  "example": "/coindesk/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "news.ts",
  "maintainers": [
    "pseudoyu"
  ],
  "module": "() => import('@/routes/coindesk/news.ts')",
  "name": "News",
  "parameters": {},
  "path": "/news",
  "radar": [
    {
      "source": [
        "coindesk.com/"
      ],
      "target": "/news"
    }
  ]
}
```
