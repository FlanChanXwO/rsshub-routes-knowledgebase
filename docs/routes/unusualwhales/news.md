# Unusual Whales - News Feed

## Coverage
`index-only`

## Route
- Namespace: `unusualwhales`
- Namespace Name: `Unusual Whales`
- Route Path: `/news`
- Route Name: `News Feed`
- Example: `/unusualwhales/news`
- URL: `unusualwhales.com/news`
- Language: `en`
- Categories: `finance`
- Maintainers: `TonyRL`
- Source Location: `news.ts`
- Source Module: `() => import('@/routes/unusualwhales/news.ts')`

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
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `unusualwhales.com/news`
  - `unusualwhales.com/`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/unusualwhales/news",
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
    "TonyRL"
  ],
  "module": "() => import('@/routes/unusualwhales/news.ts')",
  "name": "News Feed",
  "parameters": {},
  "path": "/news",
  "radar": [
    {
      "source": [
        "unusualwhales.com/news",
        "unusualwhales.com/"
      ]
    }
  ],
  "url": "unusualwhales.com/news"
}
```
