# 中国石油大学（华东） - 主页

## Coverage
`index-only`

## Route
- Namespace: `upc`
- Namespace Name: `中国石油大学（华东）`
- Route Path: `/upc/main/:type`
- Route Name: `主页`
- Example: `/upc/main/notice`
- URL: `computer.upc.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `Veagau`
- Source Location: `main.ts`
- Source Module: `_None_`

## Description
| 通知公告 | 学术动态 |
| -------- | -------- |
| notice   | scholar  |

## Parameters
- `type`: 分类，见下表


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 通知公告 | 学术动态 |\n| -------- | -------- |\n| notice   | scholar  |",
  "example": "/upc/main/notice",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "main.ts",
  "maintainers": [
    "Veagau"
  ],
  "name": "主页",
  "parameters": {
    "type": "分类，见下表"
  },
  "path": "/main/:type",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "通知公告-中国石油大学（华东） - Powered by RSSHub",
      "errorAt": "2026-01-03T09:36:38.765Z",
      "errorMessage": "[GET] \"https://news.upc.edu.cn/tzgg.htm\": <no response> fetch failed\n",
      "id": "150901439203289088",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://news.upc.edu.cn/tzgg.htm",
      "title": "通知公告-中国石油大学（华东）",
      "type": "feed",
      "url": "rsshub://upc/main/notice"
    }
  ]
}
```
