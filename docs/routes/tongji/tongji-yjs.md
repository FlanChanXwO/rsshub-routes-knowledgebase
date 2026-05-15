# 同济大学 - 研究生招生网通知公告

## Coverage
`index-only`

## Route
- Namespace: `tongji`
- Namespace Name: `同济大学`
- Route Path: `/tongji/yjs`
- Route Name: `研究生招生网通知公告`
- Example: `/tongji/yjs`
- URL: `yz.tongji.edu.cn/zsxw/ggtz.htm`
- Language: `_None_`
- Categories: `university`
- Maintainers: `shengmaosu, sitdownkevin`
- Source Location: `yjs.ts`
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
  - `yz.tongji.edu.cn/zsxw/ggtz.htm`
  - `yz.tongji.edu.cn/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/tongji/yjs",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 2,
  "location": "yjs.ts",
  "maintainers": [
    "shengmaosu",
    "sitdownkevin"
  ],
  "name": "研究生招生网通知公告",
  "parameters": {},
  "path": "/yjs",
  "radar": [
    {
      "source": [
        "yz.tongji.edu.cn/zsxw/ggtz.htm",
        "yz.tongji.edu.cn/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "同济大学研究生招生网通知公告 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "68526859637876736",
      "image": "https://upload.wikimedia.org/wikipedia/zh/f/f8/Tongji_University_Emblem.svg",
      "ownerUserId": null,
      "siteUrl": "https://yz.tongji.edu.cn/",
      "title": "同济大学研究生招生网",
      "type": "feed",
      "url": "rsshub://tongji/yjs"
    }
  ],
  "url": "yz.tongji.edu.cn/zsxw/ggtz.htm"
}
```
