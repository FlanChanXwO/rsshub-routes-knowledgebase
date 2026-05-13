# 中南财经政法大学 - 通知公告

## Coverage
`index-only`

## Route
- Namespace: `zuel`
- Namespace Name: `中南财经政法大学`
- Route Path: `/zuel/notice`
- Route Name: `通知公告`
- Example: `/zuel/notice`
- URL: `wap.zuel.edu.cn/`
- Language: `_None_`
- Categories: `university`
- Maintainers: `nczitzk`
- Source Location: `notice.ts`
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
  - `wap.zuel.edu.cn/`
  - `wap.zuel.edu.cn/notice/list.htm`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/zuel/notice",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "notice.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "通知公告",
  "parameters": {},
  "path": "/notice",
  "radar": [
    {
      "source": [
        "wap.zuel.edu.cn/",
        "wap.zuel.edu.cn/notice/list.htm"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at runNextTicks (node:internal/process/task_queues:69:3)\n    at listOnTimeout (node:internal/timers:567:9)\n    at processTimers (node:internal/timers:541:7)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "中南财经大学 - 通知公告 - Powered by RSSHub",
      "errorAt": "2025-08-14T07:34:59.187Z",
      "errorMessage": "[GET] \"http://wap.zuel.edu.cn/notice/list.htm\": <no response> fetch failed\n",
      "id": "69947206483898368",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://wap.zuel.edu.cn/notice/list.htm",
      "title": "中南财经大学 - 通知公告",
      "type": "feed",
      "url": "rsshub://zuel/notice"
    }
  ],
  "url": "wap.zuel.edu.cn/"
}
```
