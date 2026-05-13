# 知乎 - 知乎想法热榜

## Coverage
`index-only`

## Route
- Namespace: `zhihu`
- Namespace Name: `知乎`
- Route Path: `/pin/hotlist`
- Route Name: `知乎想法热榜`
- Example: `/zhihu/pin/hotlist`
- URL: `www.zhihu.com/zhihu/bookstore/newest`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `xyqfer`
- Source Location: `pin/hotlist.ts`
- Source Module: `() => import('@/routes/zhihu/pin/hotlist.ts')`

## Description
_None_

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.zhihu.com/zhihu/bookstore/newest`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/zhihu/pin/hotlist",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "pin/hotlist.ts",
  "maintainers": [
    "xyqfer"
  ],
  "module": "() => import('@/routes/zhihu/pin/hotlist.ts')",
  "name": "知乎想法热榜",
  "parameters": {},
  "path": "/pin/hotlist",
  "radar": [
    {
      "source": [
        "www.zhihu.com/zhihu/bookstore/newest"
      ]
    }
  ],
  "url": "www.zhihu.com/zhihu/bookstore/newest"
}
```
