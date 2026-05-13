# 12306 - 最新动态

## Coverage
`index-only`

## Route
- Namespace: `12306`
- Namespace Name: `12306`
- Route Path: `/12306/zxdt/:id?`
- Route Name: `最新动态`
- Example: `/12306/zxdt`
- URL: `www.12306.cn/`
- Language: `_None_`
- Categories: `travel`
- Maintainers: `LogicJake`
- Source Location: `zxdt.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 铁路局id，可在 URL 中找到，不填默认显示所有铁路局动态


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
  - `www.12306.cn/`
  - `www.12306.cn/mormhweb/1/:id/index_fl.html`
- `target`: `/zxdt/:id`

## Raw JSON
```json
{
  "categories": [
    "travel"
  ],
  "example": "/12306/zxdt",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 12,
  "location": "zxdt.ts",
  "maintainers": [
    "LogicJake"
  ],
  "name": "最新动态",
  "parameters": {
    "id": "铁路局id，可在 URL 中找到，不填默认显示所有铁路局动态"
  },
  "path": "/zxdt/:id?",
  "radar": [
    {
      "source": [
        "www.12306.cn/",
        "www.12306.cn/mormhweb/1/:id/index_fl.html"
      ],
      "target": "/zxdt/:id"
    }
  ],
  "test": {
    "code": 1,
    "message": "Error: STACK_TRACE_ERROR\n    at task (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1784:27)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1817:16)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1563:28)\n    at chain (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:599:14)\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:74:12\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:40\n    at runWithSuite (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:2258:8)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:10)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1893:54)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)"
  },
  "topFeeds": [
    {
      "description": "最新动态 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "68654231072089088",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.12306.cn/mormhweb/zxdt/index_zxdt.html",
      "title": "最新动态",
      "type": "feed",
      "url": "rsshub://12306/zxdt"
    }
  ],
  "url": "www.12306.cn/"
}
```
