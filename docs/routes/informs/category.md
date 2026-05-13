# INFORMS - Category

## Coverage
`index-only`

## Route
- Namespace: `informs`
- Namespace Name: `INFORMS`
- Route Path: `/:category?`
- Route Name: `Category`
- Example: `/informs/mnsc`
- URL: `pubsonline.informs.org`
- Language: `en`
- Categories: `journal`
- Maintainers: `Fatpandac`
- Source Location: `index.tsx`
- Source Module: `() => import('@/routes/informs/index.tsx')`

## Description
_None_

## Parameters
- `category`: Category, can be found in the url of the page, `orsc` by default


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "example": "/informs/mnsc",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.tsx",
  "maintainers": [
    "Fatpandac"
  ],
  "module": "() => import('@/routes/informs/index.tsx')",
  "name": "Category",
  "parameters": {
    "category": "Category, can be found in the url of the page, `orsc` by default"
  },
  "path": "/:category?"
}
```
