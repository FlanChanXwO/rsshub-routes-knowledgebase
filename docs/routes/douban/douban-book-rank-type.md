# 豆瓣 - 热门图书排行

## Coverage
`index-only`

## Route
- Namespace: `douban`
- Namespace Name: `豆瓣`
- Route Path: `/douban/book/rank/:type?`
- Route Name: `热门图书排行`
- Example: `/douban/book/rank/fiction`
- URL: `www.douban.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `xyqfer, queensferryme`
- Source Location: `book/rank.ts`
- Source Module: `_None_`

## Description
| 全部 | 虚构    | 非虚构     |
| ---- | ------- | ---------- |
|      | fiction | nonfiction |

## Parameters
- `type`: 图书类型，默认合并列表


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "description": "| 全部 | 虚构    | 非虚构     |\n| ---- | ------- | ---------- |\n|      | fiction | nonfiction |",
  "example": "/douban/book/rank/fiction",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 187,
  "location": "book/rank.ts",
  "maintainers": [
    "xyqfer",
    "queensferryme"
  ],
  "name": "热门图书排行",
  "parameters": {
    "type": "图书类型，默认合并列表"
  },
  "path": "/book/rank/:type?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at runNextTicks (node:internal/process/task_queues:69:3)\n    at processImmediate (node:internal/timers:472:9)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "每周一更新 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41701841005020160",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://m.douban.com/book/",
      "title": "豆瓣热门图书-全部",
      "type": "feed",
      "url": "rsshub://douban/book/rank"
    },
    {
      "description": "每周一更新 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "59787999536110592",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://m.douban.com/book/fiction",
      "title": "豆瓣热门图书-虚构类",
      "type": "feed",
      "url": "rsshub://douban/book/rank/fiction"
    }
  ]
}
```
