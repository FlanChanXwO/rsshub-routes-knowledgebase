# 机核网 - 资讯

## Coverage
`index-only`

## Route
- Namespace: `gcores`
- Namespace Name: `机核网`
- Route Path: `/news`
- Route Name: `资讯`
- Example: `/gcores/news`
- URL: `www.gcores.com`
- Language: `zh-CN`
- Categories: `game`
- Maintainers: `nczitzk`
- Source Location: `news.ts`
- Source Module: `() => import('@/routes/gcores/news.ts')`

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
  - `www.gcores.com/news`
- `target`: `/gcores/news`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "example": "/gcores/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "news.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/gcores/news.ts')",
  "name": "资讯",
  "path": "/news",
  "radar": [
    {
      "source": [
        "www.gcores.com/news"
      ],
      "target": "/gcores/news"
    }
  ],
  "url": "www.gcores.com",
  "view": 0
}
```
