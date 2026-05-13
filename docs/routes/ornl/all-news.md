# Oak Ridge National Laboratory - All News

## Coverage
`index-only`

## Route
- Namespace: `ornl`
- Namespace Name: `Oak Ridge National Laboratory`
- Route Path: `/all-news`
- Route Name: `All News`
- Example: `/ornl/all-news`
- URL: `www.ornl.gov`
- Language: `en`
- Categories: `government`
- Maintainers: `nczitzk`
- Source Location: `all-news.ts`
- Source Module: `() => import('@/routes/ornl/all-news.ts')`

## Description
_None_

## Parameters
_None_


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
  - `www.ornl.gov/all-news`
- `target`: `/all-news`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "example": "/ornl/all-news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "all-news.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/ornl/all-news.ts')",
  "name": "All News",
  "path": "/all-news",
  "radar": [
    {
      "source": [
        "www.ornl.gov/all-news"
      ],
      "target": "/all-news"
    }
  ],
  "url": "www.ornl.gov",
  "view": 0
}
```
