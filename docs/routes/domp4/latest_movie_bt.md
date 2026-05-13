# DoMP4 影视 - 最近更新的电源BT列表

## Coverage
`index-only`

## Route
- Namespace: `domp4`
- Namespace Name: `DoMP4 影视`
- Route Path: `/latest_movie_bt`
- Route Name: `最近更新的电源BT列表`
- Example: `/domp4/latest_movie_bt`
- URL: `www.xlmp4.com/`
- Language: `zh-CN`
- Categories: `multimedia`
- Maintainers: `xianghuawe, pseudoyu`
- Source Location: `latest-movie-bt.ts`
- Source Module: `() => import('@/routes/domp4/latest-movie-bt.ts')`

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
  - `www.xlmp4.com/`
  - `www.xlmp4.com/custom/update.html`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/domp4/latest_movie_bt",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": true,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "latest-movie-bt.ts",
  "maintainers": [
    "xianghuawe",
    "pseudoyu"
  ],
  "module": "() => import('@/routes/domp4/latest-movie-bt.ts')",
  "name": "最近更新的电源BT列表",
  "parameters": {},
  "path": "/latest_movie_bt",
  "radar": [
    {
      "source": [
        "www.xlmp4.com/",
        "www.xlmp4.com/custom/update.html"
      ]
    }
  ],
  "url": "www.xlmp4.com/"
}
```
