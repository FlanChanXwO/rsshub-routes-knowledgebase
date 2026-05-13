# Skebetter - Manga

## Coverage
`index-only`

## Route
- Namespace: `skebetter`
- Namespace Name: `Skebetter`
- Route Path: `/manga/:order`
- Route Name: `Manga`
- Example: `/skebetter/manga/1`
- URL: `skebetter.com`
- Language: `en`
- Categories: `anime`
- Maintainers: `SnowAgar25`
- Source Location: `manga.ts`
- Source Module: `() => import('@/routes/skebetter/manga.ts')`

## Description
| 新着 (Latest) | 人気 (Hot) |
| ---- | ---- |
| 1    | 2    |

## Parameters
- `order`: Order, see below.


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
### Rule 1
- `title`: `Manga - Latest`
- `source`:
  - `skebetter.com/series`
- `target`: `/manga/1`
### Rule 2
- `title`: `Manga - Hot`
- `source`:
  - `skebetter.com/series`
- `target`: `/manga/2`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "description": "\n| 新着 (Latest) | 人気 (Hot) |\n| ---- | ---- |\n| 1    | 2    |",
  "example": "/skebetter/manga/1",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "manga.ts",
  "maintainers": [
    "SnowAgar25"
  ],
  "module": "() => import('@/routes/skebetter/manga.ts')",
  "name": "Manga",
  "parameters": {
    "order": "Order, see below."
  },
  "path": "/manga/:order",
  "radar": [
    {
      "source": [
        "skebetter.com/series"
      ],
      "target": "/manga/1",
      "title": "Manga - Latest"
    },
    {
      "source": [
        "skebetter.com/series"
      ],
      "target": "/manga/2",
      "title": "Manga - Hot"
    }
  ]
}
```
