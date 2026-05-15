# 搜狐号 - 首页新闻

## Coverage
`index-only`

## Route
- Namespace: `sohu`
- Namespace Name: `搜狐号`
- Route Path: `/sohu/mobile`
- Route Name: `首页新闻`
- Example: `/sohu/mobile`
- URL: `sohu.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `asqwe1`
- Source Location: `mobile.ts`
- Source Module: `_None_`

## Description
订阅手机搜狐网的首页新闻

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
  - `m.sohu.com/limit`
- `target`: `/mobile`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "订阅手机搜狐网的首页新闻",
  "example": "/sohu/mobile",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 18,
  "location": "mobile.ts",
  "maintainers": [
    "asqwe1"
  ],
  "name": "首页新闻",
  "parameters": {},
  "path": "/mobile",
  "radar": [
    {
      "source": [
        "m.sohu.com/limit"
      ],
      "target": "/mobile"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected [ …(5) ] to not include 'https://m.sohu.com/a/1022337943_260616'\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.6/node_modules/@vitest/expect/dist/index.js:1319:15)\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.6/node_modules/@vitest/expect/dist/index.js:1156:15)\n    at Proxy.methodWrapper (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/chai@6.2.2/node_modules/chai/index.js:1700:25)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:67:27)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:82:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "手机搜狐新闻 - Powered by RSSHub",
      "errorAt": "2026-04-21T08:11:30.800Z",
      "errorMessage": "Failed to fetch\n",
      "id": "141055454808791040",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://m.sohu.com/limit",
      "title": "手机搜狐新闻",
      "type": "feed",
      "url": "rsshub://sohu/mobile"
    }
  ]
}
```
