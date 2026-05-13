# Anime1 - Anime

## Coverage
`index-only`

## Route
- Namespace: `anime1`
- Namespace Name: `Anime1`
- Route Path: `anime/:category/:name`
- Route Name: `Anime`
- Example: `/anime1/anime/2024年夏季/神之塔-第二季`
- URL: `anime1.me`
- Language: `zh-TW`
- Categories: `anime`
- Maintainers: `cxheng315`
- Source Location: `anime.ts`
- Source Module: `() => import('@/routes/anime1/anime.ts')`

## Description
_None_

## Parameters
- `category`: Anime1 Category
- `name`: Anime1 Name


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
  - `anime1.me/category/:category/:name`
- `target`: `/anime/:category/:name`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/anime1/anime/2024年夏季/神之塔-第二季",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "anime.ts",
  "maintainers": [
    "cxheng315"
  ],
  "module": "() => import('@/routes/anime1/anime.ts')",
  "name": "Anime",
  "parameters": {
    "category": "Anime1 Category",
    "name": "Anime1 Name"
  },
  "path": "anime/:category/:name",
  "radar": [
    {
      "source": [
        "anime1.me/category/:category/:name"
      ],
      "target": "/anime/:category/:name"
    }
  ],
  "url": "anime1.me"
}
```
