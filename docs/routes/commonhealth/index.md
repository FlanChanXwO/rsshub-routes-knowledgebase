# 康健 - 最新內容

## Coverage
`index-only`

## Route
- Namespace: `commonhealth`
- Namespace Name: `康健`
- Route Path: `/`
- Route Name: `最新內容`
- Example: `/commonhealth`
- URL: `commonhealth.com.tw`
- Language: `zh-TW`
- Categories: `traditional-media`
- Maintainers: `johan456789`
- Source Location: `index.tsx`
- Source Module: `() => import('@/routes/commonhealth/index.tsx')`

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
  - `www.commonhealth.com.tw/`
- `target`: `/`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/commonhealth",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "index.tsx",
  "maintainers": [
    "johan456789"
  ],
  "module": "() => import('@/routes/commonhealth/index.tsx')",
  "name": "最新內容",
  "path": "/",
  "radar": [
    {
      "source": [
        "www.commonhealth.com.tw/"
      ],
      "target": "/"
    }
  ],
  "url": "commonhealth.com.tw"
}
```
