# 华西医院 - 招聘公告

## Coverage
`index-only`

## Route
- Namespace: `wchscu`
- Namespace Name: `华西医院`
- Route Path: `/recruit`
- Route Name: `招聘公告`
- Example: `/wchscu/recruit`
- URL: `www.wchscu.cn`
- Language: `zh-CN`
- Categories: `other`
- Maintainers: `ViggoC`
- Source Location: `recruit.ts`
- Source Module: `() => import('@/routes/wchscu/recruit.ts')`

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
  - `www.wchscu.cn/public/notice/recruit`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "example": "/wchscu/recruit",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "recruit.ts",
  "maintainers": [
    "ViggoC"
  ],
  "module": "() => import('@/routes/wchscu/recruit.ts')",
  "name": "招聘公告",
  "path": "/recruit",
  "radar": [
    {
      "source": [
        "www.wchscu.cn/public/notice/recruit"
      ]
    }
  ],
  "url": "www.wchscu.cn"
}
```
