# 知乎 - 知乎想法 - 24 小时新闻汇总

## Coverage
`index-only`

## Route
- Namespace: `zhihu`
- Namespace Name: `知乎`
- Route Path: `/pin/daily`
- Route Name: `知乎想法 - 24 小时新闻汇总`
- Example: `/zhihu/pin/daily`
- URL: `daily.zhihu.com/*`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `xyqfer`
- Source Location: `pin/daily.ts`
- Source Module: `() => import('@/routes/zhihu/pin/daily.ts')`

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
  - `daily.zhihu.com/*`
- `target`: `/daily`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/zhihu/pin/daily",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "pin/daily.ts",
  "maintainers": [
    "xyqfer"
  ],
  "module": "() => import('@/routes/zhihu/pin/daily.ts')",
  "name": "知乎想法 - 24 小时新闻汇总",
  "parameters": {},
  "path": "/pin/daily",
  "radar": [
    {
      "source": [
        "daily.zhihu.com/*"
      ],
      "target": "/daily"
    }
  ],
  "url": "daily.zhihu.com/*"
}
```
