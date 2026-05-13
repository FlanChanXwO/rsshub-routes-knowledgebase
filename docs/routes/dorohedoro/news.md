# Dorohedoro - News

## Coverage
`index-only`

## Route
- Namespace: `dorohedoro`
- Namespace Name: `Dorohedoro`
- Route Path: `/news`
- Route Name: `News`
- Example: `/dorohedoro/news`
- URL: `dorohedoro.net/news`
- Language: `ja`
- Categories: `game`
- Maintainers: `nczitzk`
- Source Location: `news.ts`
- Source Module: `() => import('@/routes/dorohedoro/news.ts')`

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
  - `dorohedoro.net/news`
  - `dorohedoro.net/`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "example": "/dorohedoro/news",
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
  "module": "() => import('@/routes/dorohedoro/news.ts')",
  "name": "News",
  "parameters": {},
  "path": "/news",
  "radar": [
    {
      "source": [
        "dorohedoro.net/news",
        "dorohedoro.net/"
      ]
    }
  ],
  "url": "dorohedoro.net/news"
}
```
