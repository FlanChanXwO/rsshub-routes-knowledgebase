# ALICESOFT - ニュース

## Coverage
`index-only`

## Route
- Namespace: `alicesoft`
- Namespace Name: `ALICESOFT`
- Route Path: `/information/:category?/:game?`
- Route Name: `ニュース`
- Example: `/alicesoft/information/game/cat377`
- URL: `www.alicesoft.com/information`
- Language: `ja`
- Categories: `game`
- Maintainers: `keocheung`
- Source Location: `infomation.ts`
- Source Module: `() => import('@/routes/alicesoft/infomation.ts')`

## Description
_None_

## Parameters
- `category`: Category in the URL, which can be accessed under カテゴリ一覧 on the website.
- `game`: Game-specific subcategory in the URL, which can be accessed under カテゴリ一覧 on the website. In this case, the category value should be `game`.


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
  - `www.alicesoft.com/information`
  - `www.alicesoft.com/information/:category`
  - `www.alicesoft.com/information/:category/:game`
- `target`: `/information/:category/:game`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "example": "/alicesoft/information/game/cat377",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "infomation.ts",
  "maintainers": [
    "keocheung"
  ],
  "module": "() => import('@/routes/alicesoft/infomation.ts')",
  "name": "ニュース",
  "parameters": {
    "category": "Category in the URL, which can be accessed under カテゴリ一覧 on the website.",
    "game": "Game-specific subcategory in the URL, which can be accessed under カテゴリ一覧 on the website. In this case, the category value should be `game`."
  },
  "path": "/information/:category?/:game?",
  "radar": [
    {
      "source": [
        "www.alicesoft.com/information",
        "www.alicesoft.com/information/:category",
        "www.alicesoft.com/information/:category/:game"
      ],
      "target": "/information/:category/:game"
    }
  ],
  "url": "www.alicesoft.com/information"
}
```
