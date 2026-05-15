# 深圳市罗湖区人民政府 - 江苏文旅局审批公告

## Coverage
`index-only`

## Route
- Namespace: `gov`
- Namespace Name: `深圳市罗湖区人民政府`
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
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "wlt.jiangsu.gov.cn/"
}
```
