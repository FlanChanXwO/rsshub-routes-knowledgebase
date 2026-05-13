# 武汉纺织大学 - 就业信息

## Coverage
`index-only`

## Route
- Namespace: `wtu`
- Namespace Name: `武汉纺织大学`
- Route Path: `/wtu/job/:type`
- Route Name: `就业信息`
- Example: `/wtu/job/xxtz`
- URL: `wtu.91wllm.com`
- Language: `_None_`
- Categories: `university`
- Maintainers: `ticks-tan`
- Source Location: `job.ts`
- Source Module: `_None_`

## Description
| 信息类型 | 消息通知 | 通知公告 | 新闻快递 |
| -------- | -------- | -------- | -------- |
| 参数     | xxtz     | tzgg     | xwkd     |

## Parameters
- `type`: 信息类型


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
  - `wtu.91wllm.com/news/index/tag/:type`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 信息类型 | 消息通知 | 通知公告 | 新闻快递 |\n| -------- | -------- | -------- | -------- |\n| 参数     | xxtz     | tzgg     | xwkd     |",
  "example": "/wtu/job/xxtz",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "job.ts",
  "maintainers": [
    "ticks-tan"
  ],
  "name": "就业信息",
  "parameters": {
    "type": "信息类型"
  },
  "path": "/job/:type",
  "radar": [
    {
      "source": [
        "wtu.91wllm.com/news/index/tag/:type"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
