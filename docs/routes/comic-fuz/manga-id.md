# COMIC FUZ - 漫画详情

## Coverage
`index-only`

## Route
- Namespace: `comic-fuz`
- Namespace Name: `COMIC FUZ`
- Route Path: `/manga/:id`
- Route Name: `漫画详情`
- Example: `/comic-fuz/manga/218`
- URL: `comic-fuz.com`
- Language: `ja`
- Categories: `anime`
- Maintainers: `xiaobailoves`
- Source Location: `manga.ts`
- Source Module: `() => import('@/routes/comic-fuz/manga.ts')`

## Description
_None_

## Parameters
- `id`: ComicFuz中对应的漫画id


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
  - `comic-fuz.com/manga/:id`
- `target`: `/manga/:id`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/comic-fuz/manga/218",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "manga.ts",
  "maintainers": [
    "xiaobailoves"
  ],
  "module": "() => import('@/routes/comic-fuz/manga.ts')",
  "name": "漫画详情",
  "parameters": {
    "id": "ComicFuz中对应的漫画id"
  },
  "path": "/manga/:id",
  "radar": [
    {
      "source": [
        "comic-fuz.com/manga/:id"
      ],
      "target": "/manga/:id"
    }
  ]
}
```
