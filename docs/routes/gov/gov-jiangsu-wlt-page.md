# Hangzhou People's Government - 江苏文旅局审批公告

## Coverage
`index-only`

## Route
- Namespace: `gov`
- Namespace Name: `Hangzhou People's Government`
- Route Path: `/gov/jiangsu/wlt/:page?`
- Route Name: `江苏文旅局审批公告`
- Example: `/gov/jiangsu/wlt`
- URL: `wlt.jiangsu.gov.cn/`
- Language: `_None_`
- Categories: `government`
- Maintainers: `GideonSenku`
- Source Location: `jiangsu/wlt/index.tsx`
- Source Module: `_None_`

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
  "heat": 0,
  "location": "jiangsu/wlt/index.tsx",
  "maintainers": [
    "GideonSenku"
  ],
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
  "topFeeds": [],
  "url": "wlt.jiangsu.gov.cn/"
}
```
