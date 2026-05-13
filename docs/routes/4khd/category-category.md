# 4KHD - Category

## Coverage
`index-only`

## Route
- Namespace: `4khd`
- Namespace Name: `4KHD`
- Route Path: `/category/:category`
- Route Name: `Category`
- Example: `/4khd/category/cosplay`
- URL: `www.4khd.com/`
- Language: `en`
- Categories: `picture`
- Maintainers: `AiraNadih`
- Source Location: `category.ts`
- Source Module: `() => import('@/routes/4khd/category.ts')`

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
  - `www.4khd.com/pages/:category`
- `target`: `/category/:category`

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "example": "/4khd/category/cosplay",
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
  "module": "() => import('@/routes/4khd/category.ts')",
  "name": "Category",
  "parameters": {
    "category": "Category"
  },
  "path": "/category/:category",
  "radar": [
    {
      "source": [
        "www.4khd.com/pages/:category"
      ],
      "target": "/category/:category"
    }
  ],
  "url": "www.4khd.com/"
}
```
