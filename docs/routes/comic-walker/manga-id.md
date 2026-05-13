# カドコミ(Kadocomi) - 漫画详情

## Coverage
`index-only`

## Route
- Namespace: `comic-walker`
- Namespace Name: `カドコミ(Kadocomi)`
- Route Path: `/manga/:id`
- Route Name: `漫画详情`
- Example: `/comic-walker/manga/KC_006778_S`
- URL: `comic-walker.com`
- Language: `ja`
- Categories: `anime`
- Maintainers: `xiaobailoves`
- Source Location: `manga.ts`
- Source Module: `() => import('@/routes/comic-walker/manga.ts')`

## Description
_None_

## Parameters
- `id`: カドコミ(Kadocomi)中对应的作品workCode，例如 KC_006778_S


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
  - `comic-walker.com/detail/:id`
- `target`: `/manga/:id`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/comic-walker/manga/KC_006778_S",
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
  "module": "() => import('@/routes/comic-walker/manga.ts')",
  "name": "漫画详情",
  "parameters": {
    "id": "カドコミ(Kadocomi)中对应的作品workCode，例如 KC_006778_S"
  },
  "path": "/manga/:id",
  "radar": [
    {
      "source": [
        "comic-walker.com/detail/:id"
      ],
      "target": "/manga/:id"
    }
  ]
}
```
