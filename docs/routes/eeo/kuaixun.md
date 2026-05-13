# 经济观察网 - 快讯

## Coverage
`index-only`

## Route
- Namespace: `eeo`
- Namespace Name: `经济观察网`
- Route Path: `/kuaixun`
- Route Name: `快讯`
- Example: `/eeo/kuaixun`
- URL: `www.eeo.com.cn`
- Language: `zh-CN`
- Categories: `finance`
- Maintainers: `nczitzk`
- Source Location: `kuaixun.ts`
- Source Module: `() => import('@/routes/eeo/kuaixun.ts')`

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
  - `www.eeo.com.cn/kuaixun/`
- `target`: `/kuaixun`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/eeo/kuaixun",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "kuaixun.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/eeo/kuaixun.ts')",
  "name": "快讯",
  "path": "/kuaixun",
  "radar": [
    {
      "source": [
        "www.eeo.com.cn/kuaixun/"
      ],
      "target": "/kuaixun"
    }
  ],
  "url": "www.eeo.com.cn",
  "view": 0
}
```
