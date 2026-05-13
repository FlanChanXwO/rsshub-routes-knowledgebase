# 链捕手 ChainCatcher - 快讯

## Coverage
`index-only`

## Route
- Namespace: `chaincatcher`
- Namespace Name: `链捕手 ChainCatcher`
- Route Path: `/news`
- Route Name: `快讯`
- Example: `/chaincatcher/news`
- URL: `chaincatcher.com/news`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `TonyRL`
- Source Location: `news.ts`
- Source Module: `() => import('@/routes/chaincatcher/news.ts')`

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
  - `chaincatcher.com/news`
  - `chaincatcher.com/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/chaincatcher/news",
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
  "module": "() => import('@/routes/chaincatcher/news.ts')",
  "name": "快讯",
  "parameters": {},
  "path": "/news",
  "radar": [
    {
      "source": [
        "chaincatcher.com/news",
        "chaincatcher.com/"
      ]
    }
  ],
  "url": "chaincatcher.com/news"
}
```
