# 量子位 - 分类

## Coverage
`index-only`

## Route
- Namespace: `qbitai`
- Namespace Name: `量子位`
- Route Path: `/qbitai/category/:category`
- Route Name: `分类`
- Example: `/qbitai/category/资讯`
- URL: `qbitai.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `FuryMartin, Geraldxm`
- Source Location: `category.ts`
- Source Module: `_None_`

## Description
| 资讯 | 数码     | 智能车 | 智库  | 活动    |
| ---- | -------- | ------ | ----- | ------- |
| 资讯 | ebandeng | auto   | zhiku | huodong |

## Parameters
- `category`: 分类名，见下表


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
  - `qbitai.com/category/:category`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 资讯 | 数码     | 智能车 | 智库  | 活动    |\n| ---- | -------- | ------ | ----- | ------- |\n| 资讯 | ebandeng | auto   | zhiku | huodong |",
  "example": "/qbitai/category/资讯",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 389,
  "location": "category.ts",
  "maintainers": [
    "FuryMartin, Geraldxm"
  ],
  "name": "分类",
  "parameters": {
    "category": "分类名，见下表"
  },
  "path": "/category/:category",
  "radar": [
    {
      "source": [
        "qbitai.com/category/:category"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "Error: STACK_TRACE_ERROR\n    at task (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1784:27)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1817:16)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1563:28)\n    at chain (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:599:14)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:98:12\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:40\n    at runWithSuite (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:2258:8)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:10)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1893:54)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)"
  },
  "topFeeds": [
    {
      "description": "量子位 - 资讯 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "61288440756878337",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.qbitai.com/category/%E8%B5%84%E8%AE%AF",
      "title": "量子位 - 资讯",
      "type": "feed",
      "url": "rsshub://qbitai/category/%E8%B5%84%E8%AE%AF"
    },
    {
      "description": "量子位 - ebandeng - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "69701236541384704",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.qbitai.com/category/ebandeng",
      "title": "量子位 - ebandeng",
      "type": "feed",
      "url": "rsshub://qbitai/category/ebandeng"
    }
  ]
}
```
