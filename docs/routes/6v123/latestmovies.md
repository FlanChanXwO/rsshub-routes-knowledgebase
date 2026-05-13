# 6v 电影 - 最新电影

## Coverage
`index-only`

## Route
- Namespace: `6v123`
- Namespace Name: `6v 电影`
- Route Path: `/latestMovies`
- Route Name: `最新电影`
- Example: `/6v123/latestMovies`
- URL: `hao6v.com/`
- Language: `zh-CN`
- Categories: `multimedia`
- Maintainers: `tc9011`
- Source Location: `latest-movies.ts`
- Source Module: `() => import('@/routes/6v123/latest-movies.ts')`

## Description
_None_

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: true
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `hao6v.com/`
  - `hao6v.com/gvod/zx.html`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/6v123/latestMovies",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": true,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "latest-movies.ts",
  "maintainers": [
    "tc9011"
  ],
  "module": "() => import('@/routes/6v123/latest-movies.ts')",
  "name": "最新电影",
  "parameters": {},
  "path": "/latestMovies",
  "radar": [
    {
      "source": [
        "hao6v.com/",
        "hao6v.com/gvod/zx.html"
      ]
    }
  ],
  "url": "hao6v.com/"
}
```
