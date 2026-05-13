# Sakamichi Series 坂道系列官网资讯 - Hinatazaka46 News 日向坂 46 新闻

## Coverage
`index-only`

## Route
- Namespace: `hinatazaka46`
- Namespace Name: `Sakamichi Series 坂道系列官网资讯`
- Route Path: `/news`
- Route Name: `Hinatazaka46 News 日向坂 46 新闻`
- Example: `/hinatazaka46/news`
- URL: `hinatazaka46.com/s/official/news/list`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `crispgm, akashigakki`
- Source Location: `news.ts`
- Source Module: `() => import('@/routes/hinatazaka46/news.ts')`

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
  - `hinatazaka46.com/s/official/news/list`
  - `hinatazaka46.com/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/hinatazaka46/news",
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
    "crispgm",
    "akashigakki"
  ],
  "module": "() => import('@/routes/hinatazaka46/news.ts')",
  "name": "Hinatazaka46 News 日向坂 46 新闻",
  "parameters": {},
  "path": "/news",
  "radar": [
    {
      "source": [
        "hinatazaka46.com/s/official/news/list",
        "hinatazaka46.com/"
      ]
    }
  ],
  "url": "hinatazaka46.com/s/official/news/list"
}
```
