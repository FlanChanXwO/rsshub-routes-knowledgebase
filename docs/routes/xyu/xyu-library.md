# 新余学院 - 图书馆通知公告

## Coverage
`index-only`

## Route
- Namespace: `xyu`
- Namespace Name: `新余学院`
- Route Path: `/xyu/library`
- Route Name: `图书馆通知公告`
- Example: `/xyu/library`
- URL: `lib.xyc.edu.cn/index/tzgg.htm`
- Language: `_None_`
- Categories: `university`
- Maintainers: `JinMokai`
- Source Location: `library.ts`
- Source Module: `_None_`

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
  "heat": 0,
  "location": "library.ts",
  "maintainers": [
    "JinMokai"
  ],
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
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "lib.xyc.edu.cn/index/tzgg.htm"
}
```
