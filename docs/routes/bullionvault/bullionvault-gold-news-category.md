# BullionVault - Gold News

## Coverage
`index-only`

## Route
- Namespace: `bullionvault`
- Namespace Name: `BullionVault`
- Route Path: `/bullionvault/gold-news/:category?`
- Route Name: `Gold News`
- Example: `/bullionvault/gold-news`
- URL: `bullionvault.com`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `nczitzk`
- Source Location: `gold-news.ts`
- Source Module: `_None_`

## Description
::: tip
If you subscribe to [Gold Price News](https://www.bullionvault.com/gold-news/gold-price-news)，where the URL is `https://www.bullionvault.com/gold-news/gold-price-news`, extract the part `https://www.bullionvault.com/gold-news/` to the end, and use it as the parameter to fill in. Therefore, the route will be [`/bullionvault/gold-news/gold-price-news`](https://rsshub.app/bullionvault/gold-news/gold-price-news).
:::

| Category                                                                          | ID                                                                                   |
| --------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------ |
| [Opinion & Analysis](https://www.bullionvault.com/gold-news/opinion-analysis)     | [opinion-analysis](https://rsshub.app/bullionvault/gold-news/opinion-analysis)       |
| [Gold Price News](https://www.bullionvault.com/gold-news/gold-price-news)         | [gold-price-news](https://rsshub.app/bullionvault/gold-news/gold-price-news)         |
| [Investment News](https://www.bullionvault.com/gold-news/news)                    | [news](https://rsshub.app/bullionvault/gold-news/news)                               |
| [Gold Investor Index](https://www.bullionvault.com/gold-news/gold-investor-index) | [gold-investor-index](https://rsshub.app/bullionvault/gold-news/gold-investor-index) |
| [Gold Infographics](https://www.bullionvault.com/gold-news/infographics)          | [infographics](https://rsshub.app/bullionvault/gold-news/infographics)               |
| [Market Fundamentals](https://www.bullionvault.com/gold-news/market-fundamentals) | [market-fundamentals](https://rsshub.app/bullionvault/gold-news/market-fundamentals) |

## Parameters
- `category`: {"description": "Category", "options": [{"label": "Gold market analysis & gold investment research", "value": ""}, {"label": "Opinion & Analysis", "value": "opinion-analysis"}, {"label": "Gold Price News", "value": "gold-price-news"}, {"label": "Investment News", "value": "news"}, {"label": "Gold Investor Index", "value": "gold-investor-index"}, {"label": "Gold Infographics", "value": "infographics"}, {"label": "Market Fundamentals", "value": "market-fundamentals"}]}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `bullionvault.com/gold-news/:category`
### Rule 2
- `title`: `Gold market analysis & gold investment research`
- `source`:
  - `bullionvault.com/gold-news`
- `target`: `/gold-news`
### Rule 3
- `title`: `Opinion & Analysis`
- `source`:
  - `bullionvault.com/gold-news/opinion-analysis`
- `target`: `/gold-news/opinion-analysis`
### Rule 4
- `title`: `Gold Price News`
- `source`:
  - `bullionvault.com/gold-news/gold-price-news`
- `target`: `/gold-news/gold-price-news`
### Rule 5
- `title`: `Investment News`
- `source`:
  - `bullionvault.com/gold-news/news`
- `target`: `/gold-news/news`
### Rule 6
- `title`: `Gold Investor Index`
- `source`:
  - `bullionvault.com/gold-news/gold-investor-index`
- `target`: `/gold-news/gold-investor-index`
### Rule 7
- `title`: `Gold Infographics`
- `source`:
  - `bullionvault.com/gold-news/infographics`
- `target`: `/gold-news/infographics`
### Rule 8
- `title`: `Market Fundamentals`
- `source`:
  - `bullionvault.com/gold-news/market-fundamentals`
- `target`: `/gold-news/market-fundamentals`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "::: tip\nIf you subscribe to [Gold Price News](https://www.bullionvault.com/gold-news/gold-price-news)，where the URL is `https://www.bullionvault.com/gold-news/gold-price-news`, extract the part `https://www.bullionvault.com/gold-news/` to the end, and use it as the parameter to fill in. Therefore, the route will be [`/bullionvault/gold-news/gold-price-news`](https://rsshub.app/bullionvault/gold-news/gold-price-news).\n:::\n\n| Category                                                                          | ID                                                                                   |\n| --------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------ |\n| [Opinion & Analysis](https://www.bullionvault.com/gold-news/opinion-analysis)     | [opinion-analysis](https://rsshub.app/bullionvault/gold-news/opinion-analysis)       |\n| [Gold Price News](https://www.bullionvault.com/gold-news/gold-price-news)         | [gold-price-news](https://rsshub.app/bullionvault/gold-news/gold-price-news)         |\n| [Investment News](https://www.bullionvault.com/gold-news/news)                    | [news](https://rsshub.app/bullionvault/gold-news/news)                               |\n| [Gold Investor Index](https://www.bullionvault.com/gold-news/gold-investor-index) | [gold-investor-index](https://rsshub.app/bullionvault/gold-news/gold-investor-index) |\n| [Gold Infographics](https://www.bullionvault.com/gold-news/infographics)          | [infographics](https://rsshub.app/bullionvault/gold-news/infographics)               |\n| [Market Fundamentals](https://www.bullionvault.com/gold-news/market-fundamentals) | [market-fundamentals](https://rsshub.app/bullionvault/gold-news/market-fundamentals) |",
  "example": "/bullionvault/gold-news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 16,
  "location": "gold-news.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Gold News",
  "parameters": {
    "category": {
      "description": "Category",
      "options": [
        {
          "label": "Gold market analysis & gold investment research",
          "value": ""
        },
        {
          "label": "Opinion & Analysis",
          "value": "opinion-analysis"
        },
        {
          "label": "Gold Price News",
          "value": "gold-price-news"
        },
        {
          "label": "Investment News",
          "value": "news"
        },
        {
          "label": "Gold Investor Index",
          "value": "gold-investor-index"
        },
        {
          "label": "Gold Infographics",
          "value": "infographics"
        },
        {
          "label": "Market Fundamentals",
          "value": "market-fundamentals"
        }
      ]
    }
  },
  "path": "/gold-news/:category?",
  "radar": [
    {
      "source": [
        "bullionvault.com/gold-news/:category"
      ]
    },
    {
      "source": [
        "bullionvault.com/gold-news"
      ],
      "target": "/gold-news",
      "title": "Gold market analysis & gold investment research"
    },
    {
      "source": [
        "bullionvault.com/gold-news/opinion-analysis"
      ],
      "target": "/gold-news/opinion-analysis",
      "title": "Opinion & Analysis"
    },
    {
      "source": [
        "bullionvault.com/gold-news/gold-price-news"
      ],
      "target": "/gold-news/gold-price-news",
      "title": "Gold Price News"
    },
    {
      "source": [
        "bullionvault.com/gold-news/news"
      ],
      "target": "/gold-news/news",
      "title": "Investment News"
    },
    {
      "source": [
        "bullionvault.com/gold-news/gold-investor-index"
      ],
      "target": "/gold-news/gold-investor-index",
      "title": "Gold Investor Index"
    },
    {
      "source": [
        "bullionvault.com/gold-news/infographics"
      ],
      "target": "/gold-news/infographics",
      "title": "Gold Infographics"
    },
    {
      "source": [
        "bullionvault.com/gold-news/market-fundamentals"
      ],
      "target": "/gold-news/market-fundamentals",
      "title": "Market Fundamentals"
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Gold News | Gold Market Analysis & Gold Investment Research - Gold Price Commentary & Forecasts - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "129774669981528064",
      "image": "https://www.bullionvault.com/images/homepage/gold-bars-in-vault.png",
      "ownerUserId": null,
      "siteUrl": "https://bullionvault.com/gold-news",
      "title": "Gold News | Gold Market Analysis & Gold Investment Research - Gold Price Commentary & Forecasts",
      "type": "feed",
      "url": "rsshub://bullionvault/gold-news"
    }
  ],
  "url": "bullionvault.com",
  "view": 0
}
```
