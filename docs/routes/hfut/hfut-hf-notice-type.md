# 合肥工业大学 - 合肥校区通知

## Coverage
`index-only`

## Route
- Namespace: `hfut`
- Namespace Name: `合肥工业大学`
- Route Path: `/hfut/hf/notice/:type?`
- Route Name: `合肥校区通知`
- Example: `/hfut/hf/notice/tzgg`
- URL: `hfut.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `batemax`
- Source Location: `hf/notice.ts`
- Source Module: `_None_`

## Description
| 通知公告 (<https://news.hfut.edu.cn/tzgg2.htm>) | 教学科研 (<https://news.hfut.edu.cn/tzgg2/jxky.htm>) | 其他通知 (<https://news.hfut.edu.cn/tzgg2/qttz.htm>) |
| ----------------------------------------------- | ---------------------------------------------------- | ---------------------------------------------------- |
| tzgg                                            | jxky                                                 | qttz                                                 |

## Parameters
- `type`: 分类，见下表（默认为 `tzgg`)


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportRadar`: true
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `news.hfut.edu.cn`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 通知公告 (<https://news.hfut.edu.cn/tzgg2.htm>) | 教学科研 (<https://news.hfut.edu.cn/tzgg2/jxky.htm>) | 其他通知 (<https://news.hfut.edu.cn/tzgg2/qttz.htm>) |\n| ----------------------------------------------- | ---------------------------------------------------- | ---------------------------------------------------- |\n| tzgg                                            | jxky                                                 | qttz                                                 |",
  "example": "/hfut/hf/notice/tzgg",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 5,
  "location": "hf/notice.ts",
  "maintainers": [
    "batemax"
  ],
  "name": "合肥校区通知",
  "parameters": {
    "type": "分类，见下表（默认为 `tzgg`)"
  },
  "path": "/hf/notice/:type?",
  "radar": [
    {
      "source": [
        "news.hfut.edu.cn"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at runNextTicks (node:internal/process/task_queues:69:3)\n    at listOnTimeout (node:internal/timers:567:9)\n    at processTimers (node:internal/timers:541:7)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "合肥工业大学 - 通知公告 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "84842310298817536",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://news.hfut.edu.cn/tzgg2.htm",
      "title": "合肥工业大学 - 通知公告",
      "type": "feed",
      "url": "rsshub://hfut/hf/notice/tzgg"
    },
    {
      "description": "合肥工业大学 - 通知公告 - Powered by RSSHub",
      "errorAt": "2026-01-17T05:19:54.488Z",
      "errorMessage": "[GET] \"https://news.hfut.edu.cn/tzgg2.htm\": <no response> fetch failed\n",
      "id": "70797096799977472",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://news.hfut.edu.cn/tzgg2.htm",
      "title": "合肥工业大学 - 通知公告",
      "type": "feed",
      "url": "rsshub://hfut/hf/notice"
    }
  ]
}
```
