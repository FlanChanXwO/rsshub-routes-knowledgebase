# 国家能源局 - 上海市文旅局审批公告

## Coverage
`index-only`

## Route
- Namespace: `gov`
- Namespace Name: `国家能源局`
- Route Path: `/shanghai/wgj/:page?`
- Route Name: `上海市文旅局审批公告`
- Example: `/gov/sh/wgj`
- URL: `wsbs.wgj.sh.gov.cn/`
- Language: `zh-CN`
- Categories: `government`
- Maintainers: `gideonsenku`
- Source Location: `sh/wgj/wgj.tsx`
- Source Module: `() => import('@/routes/gov/sh/wgj/wgj.tsx')`

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
  - `wsbs.wgj.sh.gov.cn/`
- `target`: `/sh/wgj`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "example": "/gov/sh/wgj",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "sh/wgj/wgj.tsx",
  "maintainers": [
    "gideonsenku"
  ],
  "module": "() => import('@/routes/gov/sh/wgj/wgj.tsx')",
  "name": "上海市文旅局审批公告",
  "parameters": {
    "page": "页数，默认第 1 页"
  },
  "path": [
    "/sh/wgj/:page?",
    "/shanghai/wgj/:page?"
  ],
  "radar": [
    {
      "source": [
        "wsbs.wgj.sh.gov.cn/"
      ],
      "target": "/sh/wgj"
    }
  ],
  "url": "wsbs.wgj.sh.gov.cn/"
}
```
