# COLAMANGA - Manga

## Coverage
`index-only`

## Route
- Namespace: `colamanga`
- Namespace Name: `COLAMANGA`
- Route Path: `/:id`
- Route Name: `Manga`
- Example: `/colamanga/manga-qq978758`
- URL: `www.colamanga.com`
- Language: `zh-CN`
- Categories: `anime`
- Maintainers: `machsix`
- Source Location: `manga.ts`
- Source Module: `() => import('@/routes/colamanga/manga.ts')`

## Description
_None_

## Parameters
- `id`: 漫画id


## Features
- `requireConfig`: false
- `requirePuppeteer`: true
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.colamanga.com/:id/`
- `target`: `/:id`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/colamanga/manga-qq978758",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "manga.ts",
  "maintainers": [
    "machsix"
  ],
  "module": "() => import('@/routes/colamanga/manga.ts')",
  "name": "Manga",
  "parameters": {
    "id": "漫画id"
  },
  "path": "/:id",
  "radar": [
    {
      "source": [
        "www.colamanga.com/:id/"
      ],
      "target": "/:id"
    }
  ]
}
```
