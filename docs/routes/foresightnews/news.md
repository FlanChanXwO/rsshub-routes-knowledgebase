# Foresight News - 快讯

## Coverage
`index-only`

## Route
- Namespace: `foresightnews`
- Namespace Name: `Foresight News`
- Route Path: `/news`
- Route Name: `快讯`
- Example: `/foresightnews/news`
- URL: `foresightnews.pro/news`
- Language: `en`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `news.ts`
- Source Module: `() => import('@/routes/foresightnews/news.ts')`

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
  - `foresightnews.pro/news`
  - `foresightnews.pro/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/foresightnews/news",
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
    "nczitzk"
  ],
  "module": "() => import('@/routes/foresightnews/news.ts')",
  "name": "快讯",
  "parameters": {},
  "path": "/news",
  "radar": [
    {
      "source": [
        "foresightnews.pro/news",
        "foresightnews.pro/"
      ]
    }
  ],
  "url": "foresightnews.pro/news"
}
```
