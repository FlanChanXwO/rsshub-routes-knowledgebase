# BaoBua - Category

## Coverage
`index-only`

## Route
- Namespace: `baobua`
- Namespace Name: `BaoBua`
- Route Path: `/category/:category`
- Route Name: `Category`
- Example: `/baobua/category/network`
- URL: `baobua.com/`
- Language: `en`
- Categories: `picture`
- Maintainers: `AiraNadih`
- Source Location: `category.ts`
- Source Module: `() => import('@/routes/baobua/category.ts')`

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

## Radar
### Rule 1
- `source`:
  - `baobua.com/cat/:category`
- `target`: `/category/:category`

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "example": "/baobua/category/network",
  "features": {
    "antiCrawler": false,
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
  "module": "() => import('@/routes/baobua/category.ts')",
  "name": "Category",
  "parameters": {
    "category": "Category"
  },
  "path": "/category/:category",
  "radar": [
    {
      "source": [
        "baobua.com/cat/:category"
      ],
      "target": "/category/:category"
    }
  ],
  "url": "baobua.com/"
}
```
