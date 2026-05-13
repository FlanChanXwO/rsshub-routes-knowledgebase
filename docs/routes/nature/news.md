# Nature Journal - Nature News

## Coverage
`index-only`

## Route
- Namespace: `nature`
- Namespace Name: `Nature Journal`
- Route Path: `/news`
- Route Name: `Nature News`
- Example: `/nature/news`
- URL: `nature.com/latest-news`
- Language: `en`
- Categories: `journal`
- Maintainers: `y9c, TonyRL`
- Source Location: `news.ts`
- Source Module: `() => import('@/routes/nature/news.ts')`

## Description
_None_

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: true

## Radar
### Rule 1
- `source`:
  - `nature.com/latest-news`
  - `nature.com/news`
  - `nature.com/`

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "example": "/nature/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": true
  },
  "location": "news.ts",
  "maintainers": [
    "y9c",
    "TonyRL"
  ],
  "module": "() => import('@/routes/nature/news.ts')",
  "name": "Nature News",
  "parameters": {},
  "path": "/news",
  "radar": [
    {
      "source": [
        "nature.com/latest-news",
        "nature.com/news",
        "nature.com/"
      ]
    }
  ],
  "url": "nature.com/latest-news"
}
```
