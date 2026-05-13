# 新余学院 - 图书馆通知公告

## Coverage
`index-only`

## Route
- Namespace: `xyu`
- Namespace Name: `新余学院`
- Route Path: `/library`
- Route Name: `图书馆通知公告`
- Example: `/xyu/library`
- URL: `lib.xyc.edu.cn/index/tzgg.htm`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `JinMokai`
- Source Location: `library.ts`
- Source Module: `() => import('@/routes/xyu/library.ts')`

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
  - `lib.xyc.edu.cn/index/tzgg.htm`
- `target`: `/library`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/xyu/library",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "library.ts",
  "maintainers": [
    "JinMokai"
  ],
  "module": "() => import('@/routes/xyu/library.ts')",
  "name": "图书馆通知公告",
  "path": "/library",
  "radar": [
    {
      "source": [
        "lib.xyc.edu.cn/index/tzgg.htm"
      ],
      "target": "/library"
    }
  ],
  "url": "lib.xyc.edu.cn/index/tzgg.htm"
}
```
