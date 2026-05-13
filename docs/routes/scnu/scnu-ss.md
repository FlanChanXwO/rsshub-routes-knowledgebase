# 华南师范大学 - 软件学院通知公告

## Coverage
`index-only`

## Route
- Namespace: `scnu`
- Namespace Name: `华南师范大学`
- Route Path: `/scnu/ss`
- Route Name: `软件学院通知公告`
- Example: `/scnu/ss`
- URL: `ss.scnu.edu.cn/tongzhigonggao`
- Language: `_None_`
- Categories: `university`
- Maintainers: `shengmaosu`
- Source Location: `ss.ts`
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
  - `ss.scnu.edu.cn/tongzhigonggao`
  - `ss.scnu.edu.cn/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/scnu/ss",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 2,
  "location": "ss.ts",
  "maintainers": [
    "shengmaosu"
  ],
  "name": "软件学院通知公告",
  "parameters": {},
  "path": "/ss",
  "radar": [
    {
      "source": [
        "ss.scnu.edu.cn/tongzhigonggao",
        "ss.scnu.edu.cn/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "华南师范大学软件学院 - Powered by RSSHub",
      "errorAt": "2025-09-11T03:45:02.200Z",
      "errorMessage": "[GET] \"http://ss.scnu.edu.cn/tongzhigonggao/\": <no response> fetch failed\n",
      "id": "87005043159442432",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://ss.scnu.edu.cn/tongzhigonggao/",
      "title": "华南师范大学软件学院",
      "type": "feed",
      "url": "rsshub://scnu/ss"
    }
  ],
  "url": "ss.scnu.edu.cn/tongzhigonggao"
}
```
