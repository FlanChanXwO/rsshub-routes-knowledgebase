# Hanime1 - 每月新番

## Coverage
`index-only`

## Route
- Namespace: `hanime1`
- Namespace Name: `Hanime1`
- Route Path: `/previews/:date?`
- Route Name: `每月新番`
- Example: `/hanime1/previews/202504`
- URL: `hanime1.me`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `kjasn`
- Source Location: `previews.ts`
- Source Module: `() => import('@/routes/hanime1/previews.ts')`

## Description
_None_

## Parameters
- `date`: {"description": "日期格式为 `YYYYMM`，默认值当月"}


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
  - `hanime1.me/previews/:date`
  - `hanime1.me/previews`
- `target`: `/previews/:date`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/hanime1/previews/202504",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "previews.ts",
  "maintainers": [
    "kjasn"
  ],
  "module": "() => import('@/routes/hanime1/previews.ts')",
  "name": "每月新番",
  "parameters": {
    "date": {
      "description": "日期格式为 `YYYYMM`，默认值当月"
    }
  },
  "path": "/previews/:date?",
  "radar": [
    {
      "source": [
        "hanime1.me/previews/:date",
        "hanime1.me/previews"
      ],
      "target": "/previews/:date"
    }
  ]
}
```
