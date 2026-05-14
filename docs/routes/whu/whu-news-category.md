# 武汉大学 - 新闻网

## Coverage
`index-only`

## Route
- Namespace: `whu`
- Namespace Name: `武汉大学`
- Route Path: `/whu/news/:category{.+}?`
- Route Name: `新闻网`
- Example: `/whu/news`
- URL: `cs.whu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `None`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
category 参数可选，范围如下:

| 新闻栏目 | 武大资讯         | 学术动态    | 珞珈影像         | 武大视频         |
| -------- | ---------------- | ----------- | ---------------- | ---------------- |
| 参数     | 0 或 `wdzx/wdyw` | 1 或 `kydt` | 2 或 `stkj/ljyx` | 3 或 `stkj/wdsp` |

此外 route 后可以加上 `?limit=n` 的查询参数，表示只获取前 n 条新闻；如果不指定默认为 10。

## Parameters
- `category`: 新闻栏目，可选


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "category 参数可选，范围如下:\n\n| 新闻栏目 | 武大资讯         | 学术动态    | 珞珈影像         | 武大视频         |\n| -------- | ---------------- | ----------- | ---------------- | ---------------- |\n| 参数     | 0 或 `wdzx/wdyw` | 1 或 `kydt` | 2 或 `stkj/ljyx` | 3 或 `stkj/wdsp` |\n\n此外 route 后可以加上 `?limit=n` 的查询参数，表示只获取前 n 条新闻；如果不指定默认为 10。",
  "example": "/whu/news",
  "heat": 4,
  "location": "news.ts",
  "maintainers": [],
  "name": "新闻网",
  "parameters": {
    "category": "新闻栏目，可选"
  },
  "path": "/news/:category{.+}?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at runNextTicks (node:internal/process/task_queues:69:3)\n    at listOnTimeout (node:internal/timers:567:9)\n    at processTimers (node:internal/timers:541:7)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "武汉大学新闻网 - Powered by RSSHub",
      "errorAt": "2026-05-12T19:47:25.493Z",
      "errorMessage": "Failed to fetch\n",
      "id": "59556206825577472",
      "image": "https://news.whu.edu.cn/images/logoa.png",
      "ownerUserId": null,
      "siteUrl": "https://news.whu.edu.cn/wdzx/wdyw.htm",
      "title": "武汉大学新闻网 - 武大要闻",
      "type": "feed",
      "url": "rsshub://whu/news"
    }
  ]
}
```
