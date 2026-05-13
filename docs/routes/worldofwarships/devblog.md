# World of Warships - Development Blog

## Coverage
`index-only`

## Route
- Namespace: `worldofwarships`
- Namespace Name: `World of Warships`
- Route Path: `/devblog`
- Route Name: `Development Blog`
- Example: `/worldofwarships/devblog`
- URL: `worldofwarships.com`
- Language: `en`
- Categories: `game`
- Maintainers: `SinCerely023`
- Source Location: `devblog.ts`
- Source Module: `() => import('@/routes/worldofwarships/devblog.ts')`

## Description
_None_

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `blog.worldofwarships.com`
- `target`: `/devblog`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "example": "/worldofwarships/devblog",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "devblog.ts",
  "maintainers": [
    "SinCerely023"
  ],
  "module": "() => import('@/routes/worldofwarships/devblog.ts')",
  "name": "Development Blog",
  "path": "/devblog",
  "radar": [
    {
      "source": [
        "blog.worldofwarships.com"
      ],
      "target": "/devblog"
    }
  ]
}
```
