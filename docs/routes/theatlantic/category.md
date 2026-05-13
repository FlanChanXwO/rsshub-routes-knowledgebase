# The Atlantic - News

## Coverage
`index-only`

## Route
- Namespace: `theatlantic`
- Namespace Name: `The Atlantic`
- Route Path: `/:category`
- Route Name: `News`
- Example: `/theatlantic/latest`
- URL: `www.theatlantic.com`
- Language: `en`
- Categories: `traditional-media`
- Maintainers: `EthanWng97, pseudoyu`
- Source Location: `news.ts`
- Source Module: `() => import('@/routes/theatlantic/news.ts')`

## Description
| Popular      | Latest | Politics | Technology | Business |
| ------------ | ------ | -------- | ---------- | -------- |
| most-popular | latest | politics | technology | business |

  More categories (except photo) can be found within the navigation bar at [https://www.theatlantic.com](https://www.theatlantic.com)

## Parameters
- `category`: category, see below


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
  - `www.theatlantic.com/:category`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "| Popular      | Latest | Politics | Technology | Business |\n| ------------ | ------ | -------- | ---------- | -------- |\n| most-popular | latest | politics | technology | business |\n\n  More categories (except photo) can be found within the navigation bar at [https://www.theatlantic.com](https://www.theatlantic.com)",
  "example": "/theatlantic/latest",
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
    "EthanWng97",
    "pseudoyu"
  ],
  "module": "() => import('@/routes/theatlantic/news.ts')",
  "name": "News",
  "parameters": {
    "category": "category, see below"
  },
  "path": "/:category",
  "radar": [
    {
      "source": [
        "www.theatlantic.com/:category"
      ]
    }
  ]
}
```
