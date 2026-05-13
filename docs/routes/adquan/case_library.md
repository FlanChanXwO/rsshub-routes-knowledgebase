# 广告门 - 案例库

## Coverage
`index-only`

## Route
- Namespace: `adquan`
- Namespace Name: `广告门`
- Route Path: `/case_library`
- Route Name: `案例库`
- Example: `/adquan/case_library`
- URL: `www.adquan.com`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `case-library.ts`
- Source Module: `() => import('@/routes/adquan/case-library.ts')`

## Description
_None_

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.adquan.com/case_library/index`
- `target`: `/case_library`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/adquan/case_library",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "case-library.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/adquan/case-library.ts')",
  "name": "案例库",
  "path": "/case_library",
  "radar": [
    {
      "source": [
        "www.adquan.com/case_library/index"
      ],
      "target": "/case_library"
    }
  ],
  "url": "www.adquan.com",
  "view": 0
}
```
