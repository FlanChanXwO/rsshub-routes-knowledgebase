# finviz - US Stock News

## Coverage
`index-only`

## Route
- Namespace: `finviz`
- Namespace Name: `finviz`
- Route Path: `/finviz/news/:ticker`
- Route Name: `US Stock News`
- Example: `/finviz/news/AAPL`
- URL: `finviz.com`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `HenryQW`
- Source Location: `quote.ts`
- Source Module: `_None_`

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
  "heat": 132,
  "location": "quote.ts",
  "maintainers": [
    "HenryQW"
  ],
  "name": "US Stock News",
  "parameters": {
    "ticker": "The stock ticker"
  },
  "path": "/news/:ticker",
  "topFeeds": [
    {
      "description": "A collection of news aggregated by Finviz. - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "79424087027101706",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://finviz.com/quote.ashx?t=AAPL",
      "title": "AAPL News by Finviz",
      "type": "feed",
      "url": "rsshub://finviz/news/AAPL"
    },
    {
      "description": "A collection of news aggregated by Finviz. - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "99092999437425664",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://finviz.com/quote.ashx?t=NVDA",
      "title": "NVDA News by Finviz",
      "type": "feed",
      "url": "rsshub://finviz/news/NVDA"
    }
  ]
}
```
