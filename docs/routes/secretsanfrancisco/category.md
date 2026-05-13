# Secret San francisco - Category

## Coverage
`index-only`

## Route
- Namespace: `secretsanfrancisco`
- Namespace Name: `Secret San francisco`
- Route Path: `/:category?`
- Route Name: `Category`
- Example: `/secretsanfrancisco/top-news`
- URL: `secretsanfrancisco.com`
- Language: `en`
- Categories: `new-media`
- Maintainers: `EthanWng97`
- Source Location: `rss.tsx`
- Source Module: `() => import('@/routes/secretsanfrancisco/rss.tsx')`

## Description
_None_

## Parameters
- `category`: category name, can be found in url


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
  - `secretsanfrancisco.com/:category`
- `target`: `/:category`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/secretsanfrancisco/top-news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "rss.tsx",
  "maintainers": [
    "EthanWng97"
  ],
  "module": "() => import('@/routes/secretsanfrancisco/rss.tsx')",
  "name": "Category",
  "parameters": {
    "category": "category name, can be found in url"
  },
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "secretsanfrancisco.com/:category"
      ],
      "target": "/:category"
    }
  ]
}
```
