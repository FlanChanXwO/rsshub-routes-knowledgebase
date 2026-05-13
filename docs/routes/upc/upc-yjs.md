# 中国石油大学（华东） - 研究生院通知公告

## Coverage
`index-only`

## Route
- Namespace: `upc`
- Namespace Name: `中国石油大学（华东）`
- Route Path: `/upc/yjs`
- Route Name: `研究生院通知公告`
- Example: `/upc/yjs`
- URL: `zs.gs.upc.edu.cn/sszs/list.htm`
- Language: `_None_`
- Categories: `university`
- Maintainers: `shengmaosu`
- Source Location: `yjs.ts`
- Source Module: `_None_`

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
  - `zs.gs.upc.edu.cn/sszs/list.htm`
  - `zs.gs.upc.edu.cn/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/upc/yjs",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "yjs.ts",
  "maintainers": [
    "shengmaosu"
  ],
  "name": "研究生院通知公告",
  "parameters": {},
  "path": "/yjs",
  "radar": [
    {
      "source": [
        "zs.gs.upc.edu.cn/sszs/list.htm",
        "zs.gs.upc.edu.cn/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "中国石油大学研究生院通知公告 - Powered by RSSHub",
      "errorAt": "2026-01-03T09:32:21.150Z",
      "errorMessage": "[GET] \"http://zs.gs.upc.edu.cn/sszs/list.htm\": <no response> fetch failed\n",
      "id": "150901329485806592",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://zs.gs.upc.edu.cn/sszs/list.htm",
      "title": "中国石油大学研究生院",
      "type": "feed",
      "url": "rsshub://upc/yjs"
    }
  ],
  "url": "zs.gs.upc.edu.cn/sszs/list.htm"
}
```
