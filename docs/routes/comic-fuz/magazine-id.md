# COMIC FUZ - 杂志详情

## Coverage
`index-only`

## Route
- Namespace: `comic-fuz`
- Namespace Name: `COMIC FUZ`
- Route Path: `/magazine/:id`
- Route Name: `杂志详情`
- Example: `/comic-fuz/magazine/27860`
- URL: `comic-fuz.com`
- Language: `ja`
- Categories: `anime`
- Maintainers: `xiaobailoves`
- Source Location: `magazine.ts`
- Source Module: `() => import('@/routes/comic-fuz/magazine.ts')`

## Description
_None_

## Parameters
- `id`: ComicFuz中对应的杂志id


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
  - `comic-fuz.com/magazine/:id`
- `target`: `/magazine/:id`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/comic-fuz/magazine/27860",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "magazine.ts",
  "maintainers": [
    "xiaobailoves"
  ],
  "module": "() => import('@/routes/comic-fuz/magazine.ts')",
  "name": "杂志详情",
  "parameters": {
    "id": "ComicFuz中对应的杂志id"
  },
  "path": "/magazine/:id",
  "radar": [
    {
      "source": [
        "comic-fuz.com/magazine/:id"
      ],
      "target": "/magazine/:id"
    }
  ]
}
```
