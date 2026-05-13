# 搜狐号 - 首页新闻

## Coverage
`index-only`

## Route
- Namespace: `sohu`
- Namespace Name: `搜狐号`
- Route Path: `/mobile`
- Route Name: `首页新闻`
- Example: `/sohu/mobile`
- URL: `sohu.com`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `asqwe1`
- Source Location: `mobile.ts`
- Source Module: `() => import('@/routes/sohu/mobile.ts')`

## Description
订阅手机搜狐网的首页新闻

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
  - `m.sohu.com/limit`
- `target`: `/mobile`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "订阅手机搜狐网的首页新闻",
  "example": "/sohu/mobile",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "mobile.ts",
  "maintainers": [
    "asqwe1"
  ],
  "module": "() => import('@/routes/sohu/mobile.ts')",
  "name": "首页新闻",
  "parameters": {},
  "path": "/mobile",
  "radar": [
    {
      "source": [
        "m.sohu.com/limit"
      ],
      "target": "/mobile"
    }
  ]
}
```
