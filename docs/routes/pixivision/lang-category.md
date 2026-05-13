# pixivision - Category

## Coverage
`index-only`

## Route
- Namespace: `pixivision`
- Namespace Name: `pixivision`
- Route Path: `/:lang/:category?`
- Route Name: `Category`
- Example: `/pixivision/zh-tw`
- URL: `www.pixivision.net`
- Language: `ja`
- Categories: `anime`
- Maintainers: `SnowAgar25`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/pixivision/index.ts')`

## Description
::: tip
  `https://www.pixivision.net/zh-tw/c/interview` → `/pixivision/zh-tw/interview`
:::

## Parameters
- `lang`: Language
- `category`: Category


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
  - `www.pixivision.net/:lang`
- `target`: `/:lang`
### Rule 2
- `source`:
  - `www.pixivision.net/:lang/c/:category`
- `target`: `/:lang/:category`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "description": "::: tip\n  `https://www.pixivision.net/zh-tw/c/interview` → `/pixivision/zh-tw/interview`\n:::",
  "example": "/pixivision/zh-tw",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.ts",
  "maintainers": [
    "SnowAgar25"
  ],
  "module": "() => import('@/routes/pixivision/index.ts')",
  "name": "Category",
  "parameters": {
    "category": "Category",
    "lang": "Language"
  },
  "path": "/:lang/:category?",
  "radar": [
    {
      "source": [
        "www.pixivision.net/:lang"
      ],
      "target": "/:lang"
    },
    {
      "source": [
        "www.pixivision.net/:lang/c/:category"
      ],
      "target": "/:lang/:category"
    }
  ],
  "view": 0
}
```
