# 每经网 - 分类

## Coverage
`index-only`

## Route
- Namespace: `nbd`
- Namespace Name: `每经网`
- Route Path: `/nbd/:id?`
- Route Name: `分类`
- Example: `/nbd`
- URL: `nbd.com.cn/`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| 头条 | 要闻 | 图片新闻 | 推荐 |
| ---- | ---- | -------- | ---- |
| 2    | 3    | 4        | 5    |

## Parameters
- `id`: 分类 id，见下表，默认为要闻


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
  - `nbd.com.cn/`
  - `nbd.com.cn/columns/:id?`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "| 头条 | 要闻 | 图片新闻 | 推荐 |\n| ---- | ---- | -------- | ---- |\n| 2    | 3    | 4        | 5    |",
  "example": "/nbd",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 13,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "分类",
  "parameters": {
    "id": "分类 id，见下表，默认为要闻"
  },
  "path": "/:id?",
  "radar": [
    {
      "source": [
        "nbd.com.cn/",
        "nbd.com.cn/columns/:id?"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "Error: STACK_TRACE_ERROR\n    at task (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1784:27)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1817:16)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1563:28)\n    at chain (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:599:14)\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:74:12\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:40\n    at runWithSuite (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:2258:8)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:10)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1893:54)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)"
  },
  "topFeeds": [
    {
      "description": "undefined - Powered by RSSHub",
      "errorAt": "2024-11-12T16:29:48.931Z",
      "errorMessage": "503 Service Unavailable\n503 Service Unavailable\n",
      "id": "69296270546855936",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://docs.rsshub.app/",
      "title": "RSSHub",
      "type": "feed",
      "url": "rsshub://nbd/daily"
    },
    {
      "description": null,
      "errorAt": "2025-08-21T07:38:04.685Z",
      "errorMessage": "Cannot read properties of undefined (reading 'startsWith')\n",
      "id": "181211868868349952",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://nbd"
    }
  ],
  "url": "nbd.com.cn/"
}
```
