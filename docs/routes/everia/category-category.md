# EVERIA.CLUB - Images with category

## Coverage
`index-only`

## Route
- Namespace: `everia`
- Namespace Name: `EVERIA.CLUB`
- Route Path: `/category/:category`
- Route Name: `Images with category`
- Example: `/everia/category/cosplay`
- URL: `everia.club`
- Language: `_None_`
- Categories: `picture`
- Maintainers: `KTachibanaM, AiraNadih`
- Source Location: `category.ts`
- Source Module: `() => import('@/routes/everia/category.ts')`

## Description
_None_

## Parameters
- `category`: Category of the image stream


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
  - `everia.club/category/:category`
- `target`: `/category/:category`

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "example": "/everia/category/cosplay",
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
    "KTachibanaM",
    "AiraNadih"
  ],
  "module": "() => import('@/routes/everia/category.ts')",
  "name": "Images with category",
  "parameters": {
    "category": "Category of the image stream"
  },
  "path": "/category/:category",
  "radar": [
    {
      "source": [
        "everia.club/category/:category"
      ],
      "target": "/category/:category"
    }
  ]
}
```
