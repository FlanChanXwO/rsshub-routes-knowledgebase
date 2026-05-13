# U3C3 - Search

## Coverage
`index-only`

## Route
- Namespace: `u3c3`
- Namespace Name: `U3C3`
- Route Path: `/search/:keyword/:preview?`
- Route Name: `Search`
- Example: `/u3c3/search/新片速递`
- URL: `u3c3.com`
- Language: `zh-CN`
- Categories: `multimedia`
- Maintainers: `storytellerF`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/u3c3/index.ts')`

## Description
_None_

## Parameters
- `keyword`: Search keyword
- `preview`: Show image preview, off by default, non empty value means on


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: true
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/u3c3/search/新片速递",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": true,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.ts",
  "maintainers": [
    "storytellerF"
  ],
  "module": "() => import('@/routes/u3c3/index.ts')",
  "name": "Search",
  "parameters": {
    "keyword": "Search keyword",
    "preview": "Show image preview, off by default, non empty value means on"
  },
  "path": [
    "/search/:keyword/:preview?",
    "/:type?/:preview?"
  ]
}
```
