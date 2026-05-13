# 停水通知 - 杭州市

## Coverage
`index-only`

## Route
- Namespace: `tingshuitz`
- Namespace Name: `停水通知`
- Route Path: `/hangzhou`
- Route Name: `杭州市`
- Example: `/tingshuitz/hangzhou`
- URL: `www.hzwgc.com/public/stop_the_water`
- Language: `zh-CN`
- Categories: `forecast`
- Maintainers: `znhocn`
- Source Location: `hangzhou.ts`
- Source Module: `() => import('@/routes/tingshuitz/hangzhou.ts')`

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
  - `www.hzwgc.com/public/stop_the_water`
  - `www.hzwgc.com/`

## Raw JSON
```json
{
  "categories": [
    "forecast"
  ],
  "example": "/tingshuitz/hangzhou",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "hangzhou.ts",
  "maintainers": [
    "znhocn"
  ],
  "module": "() => import('@/routes/tingshuitz/hangzhou.ts')",
  "name": "杭州市",
  "parameters": {},
  "path": "/hangzhou",
  "radar": [
    {
      "source": [
        "www.hzwgc.com/public/stop_the_water",
        "www.hzwgc.com/"
      ]
    }
  ],
  "url": "www.hzwgc.com/public/stop_the_water"
}
```
