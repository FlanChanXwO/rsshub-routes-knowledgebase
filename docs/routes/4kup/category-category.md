# 4KUP - Category

## Coverage
`index-only`

## Route
- Namespace: `4kup`
- Namespace Name: `4KUP`
- Route Path: `/category/:category`
- Route Name: `Category`
- Example: `/4kup/category/coser`
- URL: `4kup.net/`
- Language: `en`
- Categories: `picture`
- Maintainers: `AiraNadih`
- Source Location: `category.ts`
- Source Module: `() => import('@/routes/4kup/category.ts')`

## Description
_None_

## Parameters
- `category`: Category


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
- `source`:
  - `4kup.net/category/:category`
- `target`: `/category/:category`

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "example": "/4kup/category/coser",
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
    "AiraNadih"
  ],
  "module": "() => import('@/routes/4kup/category.ts')",
  "name": "Category",
  "parameters": {
    "category": "Category"
  },
  "path": "/category/:category",
  "radar": [
    {
      "source": [
        "4kup.net/category/:category"
      ],
      "target": "/category/:category"
    }
  ],
  "url": "4kup.net/"
}
```
