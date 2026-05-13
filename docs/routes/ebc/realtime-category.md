# 東森新聞 - 即時新聞

## Coverage
`index-only`

## Route
- Namespace: `ebc`
- Namespace Name: `東森新聞`
- Route Path: `/realtime/:category?`
- Route Name: `即時新聞`
- Example: `/ebc/realtime/politics`
- URL: `ebc.net.tw`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `quiniapiezoelectricity`
- Source Location: `realtime.ts`
- Source Module: `() => import('@/routes/ebc/realtime.ts')`

## Description
_None_

## Parameters
- `category`: Category from the last segment of the URL of the corresponding site


## Features
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `requireConfig`: false

## Radar
### Rule 1
- `source`:
  - `news.ebc.net.tw/realtime/:category`
- `target`: `/:category`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "",
  "example": "/ebc/realtime/politics",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "realtime.ts",
  "maintainers": [
    "quiniapiezoelectricity"
  ],
  "module": "() => import('@/routes/ebc/realtime.ts')",
  "name": "即時新聞",
  "parameters": {
    "category": "Category from the last segment of the URL of the corresponding site"
  },
  "path": "/realtime/:category?",
  "radar": [
    {
      "source": [
        "news.ebc.net.tw/realtime/:category"
      ],
      "target": "/:category"
    }
  ]
}
```
