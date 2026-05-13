# 蓝点网 - 首页

## Coverage
`index-only`

## Route
- Namespace: `landiannews`
- Namespace Name: `蓝点网`
- Route Path: `/`
- Route Name: `首页`
- Example: `/landiannews`
- URL: `www.landiannews.com`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `nczitzk, cscnk52`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/landiannews/index.ts')`

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
  - `www.landiannews.com`
- `target`: `/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/landiannews",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "index.ts",
  "maintainers": [
    "nczitzk",
    "cscnk52"
  ],
  "module": "() => import('@/routes/landiannews/index.ts')",
  "name": "首页",
  "path": "/",
  "radar": [
    {
      "source": [
        "www.landiannews.com"
      ],
      "target": "/"
    }
  ],
  "url": "www.landiannews.com",
  "view": 0
}
```
