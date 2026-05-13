# qBittorrent - News

## Coverage
`index-only`

## Route
- Namespace: `qbittorrent`
- Namespace Name: `qBittorrent`
- Route Path: `/news`
- Route Name: `News`
- Example: `/qbittorrent/news`
- URL: `qbittorrent.org/news.php`
- Language: `en`
- Categories: `program-update`
- Maintainers: `TonyRL`
- Source Location: `news.ts`
- Source Module: `() => import('@/routes/qbittorrent/news.ts')`

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
  - `qbittorrent.org/news.php`
  - `qbittorrent.org/`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "example": "/qbittorrent/news",
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
  "module": "() => import('@/routes/qbittorrent/news.ts')",
  "name": "News",
  "parameters": {},
  "path": "/news",
  "radar": [
    {
      "source": [
        "qbittorrent.org/news.php",
        "qbittorrent.org/"
      ]
    }
  ],
  "url": "qbittorrent.org/news.php"
}
```
