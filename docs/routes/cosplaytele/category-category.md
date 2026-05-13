# CosplayTele - Category

## Coverage
`index-only`

## Route
- Namespace: `cosplaytele`
- Namespace Name: `CosplayTele`
- Route Path: `/category/:category`
- Route Name: `Category`
- Example: `/cosplaytele/category/cosplay`
- URL: `cosplaytele.com/`
- Language: `en`
- Categories: `picture`
- Maintainers: `AiraNadih`
- Source Location: `category.ts`
- Source Module: `() => import('@/routes/cosplaytele/category.ts')`

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
  - `cosplaytele.com/category/:category`
- `target`: `/category/:category`

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "example": "/cosplaytele/category/cosplay",
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
  "module": "() => import('@/routes/cosplaytele/category.ts')",
  "name": "Category",
  "parameters": {
    "category": "Category"
  },
  "path": "/category/:category",
  "radar": [
    {
      "source": [
        "cosplaytele.com/category/:category"
      ],
      "target": "/category/:category"
    }
  ],
  "url": "cosplaytele.com/"
}
```
