# 国家能源局 - 江苏文旅局审批公告

## Coverage
`index-only`

## Route
- Namespace: `gov`
- Namespace Name: `国家能源局`
- Route Path: `/jiangsu/wlt/:page?`
- Route Name: `江苏文旅局审批公告`
- Example: `/gov/jiangsu/wlt`
- URL: `wlt.jiangsu.gov.cn/`
- Language: `zh-CN`
- Categories: `government`
- Maintainers: `GideonSenku`
- Source Location: `jiangsu/wlt/index.tsx`
- Source Module: `() => import('@/routes/gov/jiangsu/wlt/index.tsx')`

## Description
_None_

## Parameters
- `page`: 页数，默认第 1 页


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
  - `wlt.jiangsu.gov.cn/`
- `target`: `/jiangsu/wlt`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "example": "/gov/jiangsu/wlt",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "jiangsu/wlt/index.tsx",
  "maintainers": [
    "GideonSenku"
  ],
  "module": "() => import('@/routes/gov/jiangsu/wlt/index.tsx')",
  "name": "江苏文旅局审批公告",
  "parameters": {
    "page": "页数，默认第 1 页"
  },
  "path": "/jiangsu/wlt/:page?",
  "radar": [
    {
      "source": [
        "wlt.jiangsu.gov.cn/"
      ],
      "target": "/jiangsu/wlt"
    }
  ],
  "url": "wlt.jiangsu.gov.cn/"
}
```
