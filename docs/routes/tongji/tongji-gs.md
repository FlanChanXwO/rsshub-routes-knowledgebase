# 同济大学 - 研究生院通知公告

## Coverage
`index-only`

## Route
- Namespace: `tongji`
- Namespace Name: `同济大学`
- Route Path: `/tongji/gs`
- Route Name: `研究生院通知公告`
- Example: `/tongji/gs`
- URL: `gs.tongji.edu.cn/tzgg.htm`
- Language: `_None_`
- Categories: `university`
- Maintainers: `sitdownkevin`
- Source Location: `gs.ts`
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
  - `gs.tongji.edu.cn/tzgg.htm`
  - `gs.tongji.edu.cn/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/tongji/gs",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 3,
  "location": "gs.ts",
  "maintainers": [
    "sitdownkevin"
  ],
  "name": "研究生院通知公告",
  "parameters": {},
  "path": "/gs",
  "radar": [
    {
      "source": [
        "gs.tongji.edu.cn/tzgg.htm",
        "gs.tongji.edu.cn/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "同济大学研究生院通知公告 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "104772158131144704",
      "image": "https://upload.wikimedia.org/wikipedia/zh/f/f8/Tongji_University_Emblem.svg",
      "ownerUserId": null,
      "siteUrl": "https://gs.tongji.edu.cn/",
      "title": "同济大学研究生院",
      "type": "feed",
      "url": "rsshub://tongji/gs"
    }
  ],
  "url": "gs.tongji.edu.cn/tzgg.htm"
}
```
