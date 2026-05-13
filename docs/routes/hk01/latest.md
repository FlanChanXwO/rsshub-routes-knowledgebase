# 香港 01 - 即時

## Coverage
`index-only`

## Route
- Namespace: `hk01`
- Namespace Name: `香港 01`
- Route Path: `/latest`
- Route Name: `即時`
- Example: `/hk01/latest`
- URL: `hk01.com/latest`
- Language: `zh-HK`
- Categories: `new-media`
- Maintainers: `5upernova-heng`
- Source Location: `latest.ts`
- Source Module: `() => import('@/routes/hk01/latest.ts')`

## Description
_None_

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `hk01.com/latest`
  - `hk01.com/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/hk01/latest",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "latest.ts",
  "maintainers": [
    "5upernova-heng"
  ],
  "module": "() => import('@/routes/hk01/latest.ts')",
  "name": "即時",
  "parameters": {},
  "path": "/latest",
  "radar": [
    {
      "source": [
        "hk01.com/latest",
        "hk01.com/"
      ]
    }
  ],
  "url": "hk01.com/latest"
}
```
