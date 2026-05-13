# 天下雜誌 - 最新上線

## Coverage
`index-only`

## Route
- Namespace: `cw`
- Namespace Name: `天下雜誌`
- Route Path: `/today`
- Route Name: `最新上線`
- Example: `/cw/today`
- URL: `cw.com.tw/today`
- Language: `zh-TW`
- Categories: `traditional-media`
- Maintainers: `TonyRL`
- Source Location: `today.ts`
- Source Module: `() => import('@/routes/cw/today.ts')`

## Description
_None_

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: true
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `cw.com.tw/today`
  - `cw.com.tw/`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/cw/today",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "today.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/cw/today.ts')",
  "name": "最新上線",
  "parameters": {},
  "path": "/today",
  "radar": [
    {
      "source": [
        "cw.com.tw/today",
        "cw.com.tw/"
      ]
    }
  ],
  "url": "cw.com.tw/today"
}
```
