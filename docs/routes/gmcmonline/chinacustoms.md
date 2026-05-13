# 国门传媒在线 - 中国海关

## Coverage
`index-only`

## Route
- Namespace: `gmcmonline`
- Namespace Name: `国门传媒在线`
- Route Path: `/chinacustoms`
- Route Name: `中国海关`
- Example: `/gmcmonline/chinacustoms`
- URL: `chinacustoms.gmcmonline.com`
- Language: `zh-CN`
- Categories: `reading`
- Maintainers: `nczitzk`
- Source Location: `chinacustoms.ts`
- Source Module: `() => import('@/routes/gmcmonline/chinacustoms.ts')`

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
  - `chinacustoms.gmcmonline.com`
- `target`: `/chinacustoms`

## Raw JSON
```json
{
  "categories": [
    "reading"
  ],
  "example": "/gmcmonline/chinacustoms",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "chinacustoms.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/gmcmonline/chinacustoms.ts')",
  "name": "中国海关",
  "path": "/chinacustoms",
  "radar": [
    {
      "source": [
        "chinacustoms.gmcmonline.com"
      ],
      "target": "/chinacustoms"
    }
  ],
  "url": "chinacustoms.gmcmonline.com"
}
```
