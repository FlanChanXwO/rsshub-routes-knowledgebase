# 乳首ふぇち - Category

## Coverage
`index-only`

## Route
- Namespace: `chikubi`
- Namespace Name: `乳首ふぇち`
- Route Path: `/category/:keyword`
- Route Name: `Category`
- Example: `/chikubi/category/nipple-lesbian`
- URL: `chikubi.jp`
- Language: `ja`
- Categories: `multimedia`
- Maintainers: `SnowAgar25`
- Source Location: `category.ts`
- Source Module: `() => import('@/routes/chikubi/category.ts')`

## Description
_None_

## Parameters
- `keyword`: Keyword


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
- `title`: `Category`
- `source`:
  - `chikubi.jp/category/:keyword`
- `target`: `/category/:keyword`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/chikubi/category/nipple-lesbian",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "category.ts",
  "maintainers": [
    "SnowAgar25"
  ],
  "module": "() => import('@/routes/chikubi/category.ts')",
  "name": "Category",
  "parameters": {
    "keyword": "Keyword"
  },
  "path": "/category/:keyword",
  "radar": [
    {
      "source": [
        "chikubi.jp/category/:keyword"
      ],
      "target": "/category/:keyword",
      "title": "Category"
    }
  ]
}
```
