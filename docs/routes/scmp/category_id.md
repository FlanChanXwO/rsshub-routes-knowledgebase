# Corona Virus Disease 2019 - News

## Coverage
`index-only`

## Route
- Namespace: `scmp`
- Namespace Name: `Corona Virus Disease 2019`
- Route Path: `/:category_id`
- Route Name: `News`
- Example: `/scmp/3`
- URL: `scmp.com`
- Language: `en`
- Categories: `traditional-media`
- Maintainers: `proletarius101`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/scmp/index.ts')`

## Description
See the [official RSS page](https://www.scmp.com/rss) to get the ID of each category. This route provides fulltext that the offical feed doesn't.

## Parameters
- `category_id`: Category


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
  - `scmp.com/rss/:category_id/feed`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "See the [official RSS page](https://www.scmp.com/rss) to get the ID of each category. This route provides fulltext that the offical feed doesn't.",
  "example": "/scmp/3",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.ts",
  "maintainers": [
    "proletarius101"
  ],
  "module": "() => import('@/routes/scmp/index.ts')",
  "name": "News",
  "parameters": {
    "category_id": "Category"
  },
  "path": "/:category_id",
  "radar": [
    {
      "source": [
        "scmp.com/rss/:category_id/feed"
      ]
    }
  ]
}
```
