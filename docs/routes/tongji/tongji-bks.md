# 同济大学 - 本科生院通知公告

## Coverage
`index-only`

## Route
- Namespace: `tongji`
- Namespace Name: `同济大学`
- Route Path: `/tongji/bks`
- Route Name: `本科生院通知公告`
- Example: `/tongji/bks`
- URL: `bksy.tongji.edu.cn/`
- Language: `_None_`
- Categories: `university`
- Maintainers: `shiquda`
- Source Location: `bks.ts`
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
  - `bksy.tongji.edu.cn/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/tongji/bks",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "bks.ts",
  "maintainers": [
    "shiquda"
  ],
  "name": "本科生院通知公告",
  "parameters": {},
  "path": "/bks",
  "radar": [
    {
      "source": [
        "bksy.tongji.edu.cn/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "同济大学本科生院通知公告 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "56948849407992833",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://bksy.tongji.edu.cn/30359/list.htm",
      "title": "同济大学本科生院",
      "type": "feed",
      "url": "rsshub://tongji/bks"
    }
  ],
  "url": "bksy.tongji.edu.cn/"
}
```
