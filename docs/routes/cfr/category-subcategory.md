# Council on Foreign Relations - News

## Coverage
`index-only`

## Route
- Namespace: `cfr`
- Namespace Name: `Council on Foreign Relations`
- Route Path: `/:category/:subCategory?`
- Route Name: `News`
- Example: `/cfr/asia`
- URL: `www.cfr.org`
- Language: `en`
- Categories: `traditional-media`
- Maintainers: `KarasuShin`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/cfr/index.ts')`

## Description
_None_

## Parameters
- `category`: category, find it in the URL
- `subCategory`: sub-category, find it in the URL


## Features
- `antiCrawler`: true

## Radar
### Rule 1
- `source`:
  - `www.cfr.org/:category`
  - `www.cfr.org/:category/:subCategory`
- `target`: `/:category/:subCategory?`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/cfr/asia",
  "features": {
    "antiCrawler": true
  },
  "location": "index.ts",
  "maintainers": [
    "KarasuShin"
  ],
  "module": "() => import('@/routes/cfr/index.ts')",
  "name": "News",
  "parameters": {
    "category": "category, find it in the URL",
    "subCategory": "sub-category, find it in the URL"
  },
  "path": "/:category/:subCategory?",
  "radar": [
    {
      "source": [
        "www.cfr.org/:category",
        "www.cfr.org/:category/:subCategory"
      ],
      "target": "/:category/:subCategory?"
    }
  ]
}
```
