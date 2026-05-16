# CoinDesk - News

## Coverage
`index-only`

## Route
- Namespace: `coindesk`
- Namespace Name: `CoinDesk`
- Route Path: `/coindesk/news`
- Route Name: `News`
- Example: `/coindesk/news`
- URL: `coindesk.com`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `pseudoyu`
- Source Location: `news.ts`
- Source Module: `_None_`

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
  "heat": 85,
  "location": "news.ts",
  "maintainers": [
    "pseudoyu"
  ],
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
  ],
  "topFeeds": [
    {
      "description": "Leader in cryptocurrency, Bitcoin, Ethereum, XRP, blockchain, DeFi, digital finance and Web 3.0 news with analysis, video and live price updates. - Powered by RSSHub",
      "errorAt": "2026-05-14T21:56:42.058Z",
      "errorMessage": "[GET] \"https://www.coindesk.com/business/2026/05/14/here-is-why-wall-street-is-racing-to-tokenize-the-entire-stock-market\": 429 Too Many Requests\n[GET] \"https://www.coindesk.com/policy/2026/05/14/u-s-senators-lament-failure-to-win-bipartisan-support-yet-on-crypto-clarity-act\": 429 Too Many Requests\n",
      "id": "126922928969806848",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.coindesk.com/",
      "title": "CoinDesk: Bitcoin, Ethereum, Crypto News and Price Data",
      "type": "feed",
      "url": "rsshub://coindesk/news"
    }
  ]
}
```
