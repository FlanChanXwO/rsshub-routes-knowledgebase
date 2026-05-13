# finviz - US Stock News

## Coverage
`index-only`

## Route
- Namespace: `finviz`
- Namespace Name: `finviz`
- Route Path: `/news/:ticker`
- Route Name: `US Stock News`
- Example: `/finviz/news/AAPL`
- URL: `finviz.com`
- Language: `en`
- Categories: `finance`
- Maintainers: `HenryQW`
- Source Location: `quote.ts`
- Source Module: `() => import('@/routes/finviz/quote.ts')`

## Description
_None_

## Parameters
- `ticker`: The stock ticker


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/finviz/news/AAPL",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "quote.ts",
  "maintainers": [
    "HenryQW"
  ],
  "module": "() => import('@/routes/finviz/quote.ts')",
  "name": "US Stock News",
  "parameters": {
    "ticker": "The stock ticker"
  },
  "path": "/news/:ticker"
}
```
