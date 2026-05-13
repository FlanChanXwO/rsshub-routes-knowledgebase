# 北京天文馆 - 每日一图

## Coverage
`index-only`

## Route
- Namespace: `bjp`
- Namespace Name: `北京天文馆`
- Route Path: `/apod`
- Route Name: `每日一图`
- Example: `/bjp/apod`
- URL: `bjp.org.cn/APOD/today.shtml`
- Language: `zh-CN`
- Categories: `picture`
- Maintainers: `HenryQW`
- Source Location: `apod.ts`
- Source Module: `() => import('@/routes/bjp/apod.ts')`

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
  - `bjp.org.cn/APOD/today.shtml`
  - `bjp.org.cn/APOD/list.shtml`
  - `bjp.org.cn/`

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "example": "/bjp/apod",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "apod.ts",
  "maintainers": [
    "HenryQW"
  ],
  "module": "() => import('@/routes/bjp/apod.ts')",
  "name": "每日一图",
  "parameters": {},
  "path": "/apod",
  "radar": [
    {
      "source": [
        "bjp.org.cn/APOD/today.shtml",
        "bjp.org.cn/APOD/list.shtml",
        "bjp.org.cn/"
      ]
    }
  ],
  "url": "bjp.org.cn/APOD/today.shtml",
  "view": 2
}
```
