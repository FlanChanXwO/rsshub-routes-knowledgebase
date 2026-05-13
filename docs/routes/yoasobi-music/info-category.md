# Yoasobi Official - News & Biography

## Coverage
`index-only`

## Route
- Namespace: `yoasobi-music`
- Namespace Name: `Yoasobi Official`
- Route Path: `/info/:category?`
- Route Name: `News & Biography`
- Example: `/yoasobi-music/info/news`
- URL: `www.yoasobi-music.jp/`
- Language: `ja`
- Categories: `live`
- Maintainers: `None`
- Source Location: `info.tsx`
- Source Module: `() => import('@/routes/yoasobi-music/info.tsx')`

## Description
_None_

## Parameters
- `category`: `news`, `biography`


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
  - `www.yoasobi-music.jp/`
  - `www.yoasobi-music.jp/:category`
- `target`: `/info/:category`

## Raw JSON
```json
{
  "categories": [
    "live"
  ],
  "example": "/yoasobi-music/info/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "info.tsx",
  "maintainers": [],
  "module": "() => import('@/routes/yoasobi-music/info.tsx')",
  "name": "News & Biography",
  "parameters": {
    "category": "`news`, `biography`"
  },
  "path": "/info/:category?",
  "radar": [
    {
      "source": [
        "www.yoasobi-music.jp/",
        "www.yoasobi-music.jp/:category"
      ],
      "target": "/info/:category"
    }
  ],
  "url": "www.yoasobi-music.jp/"
}
```
