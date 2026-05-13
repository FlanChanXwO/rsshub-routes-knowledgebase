# Uniqlo - New Arrivals

## Coverage
`index-only`

## Route
- Namespace: `uniqlo`
- Namespace Name: `Uniqlo`
- Route Path: `/new/:country/:category`
- Route Name: `New Arrivals`
- Example: `/uniqlo/new/sg/men`
- URL: `www.uniqlo.com`
- Language: `en`
- Categories: `shopping`
- Maintainers: `DIYgod`
- Source Location: `new.ts`
- Source Module: `() => import('@/routes/uniqlo/new.ts')`

## Description
_None_

## Parameters
- `country`: currently only supports sg, us, jp
- `category`: supports `men` `women`, `kids`, `baby`


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
    "shopping"
  ],
  "example": "/uniqlo/new/sg/men",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "new.ts",
  "maintainers": [
    "DIYgod"
  ],
  "module": "() => import('@/routes/uniqlo/new.ts')",
  "name": "New Arrivals",
  "parameters": {
    "category": "supports `men` `women`, `kids`, `baby`",
    "country": "currently only supports sg, us, jp"
  },
  "path": "/new/:country/:category"
}
```
