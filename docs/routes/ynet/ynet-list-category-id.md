# 北青网 - 列表

## Coverage
`index-only`

## Route
- Namespace: `ynet`
- Namespace Name: `北青网`
- Route Path: `/ynet/list/:category?/:id?`
- Route Name: `列表`
- Example: `/ynet/list/news/2121t76`
- URL: `ynet.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `list.ts`
- Source Module: `_None_`

## Description
::: tip
订阅 [北青快讯](https://news.ynet.com/list/2121t76.html)，其源网址为 `https://news.ynet.com/list/2121t76.html`，请参考该 URL 指定部分构成参数，此时路由为 [`/ynet/list/news/2121t76`](https://rsshub.app/ynet/list/news/2121t76)。
:::

## Parameters
- `category`: {"description": "分类，默认为 `news`，可在对应分类页 URL 中找到"}
- `id`: {"description": "列表 ID，可在对应列表页 URL 中找到"}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `ynet.com`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "::: tip\n订阅 [北青快讯](https://news.ynet.com/list/2121t76.html)，其源网址为 `https://news.ynet.com/list/2121t76.html`，请参考该 URL 指定部分构成参数，此时路由为 [`/ynet/list/news/2121t76`](https://rsshub.app/ynet/list/news/2121t76)。\n:::",
  "example": "/ynet/list/news/2121t76",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 0,
  "location": "list.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "列表",
  "parameters": {
    "category": {
      "description": "分类，默认为 `news`，可在对应分类页 URL 中找到"
    },
    "id": {
      "description": "列表 ID，可在对应列表页 URL 中找到"
    }
  },
  "path": "/list/:category?/:id?",
  "radar": [
    {
      "source": [
        "ynet.com"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "Error: STACK_TRACE_ERROR\n    at task (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1784:27)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1817:16)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1563:28)\n    at chain (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:599:14)\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:74:12\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:40\n    at runWithSuite (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:2258:8)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:10)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1893:54)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)"
  },
  "topFeeds": [],
  "url": "ynet.com",
  "view": 0
}
```
