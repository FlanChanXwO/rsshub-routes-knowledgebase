# Nanjing University of the Arts 南京艺术学院 - Library

## Coverage
`index-only`

## Route
- Namespace: `nua`
- Namespace Name: `Nanjing University of the Arts 南京艺术学院`
- Route Path: `/nua/lib/:type`
- Route Name: `Library`
- Example: `/nua/lib/xwdt`
- URL: `index.nua.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `evnydd0sf`
- Source Location: `lib.ts`
- Source Module: `_None_`

## Description
| News Type | Parameters |
| --------- | ---------- |
| 新闻动态  | xwdt       |
| 党建动态  | djdt       |
| 资源动态  | zydt       |
| 服务动态  | fwdt       |

## Parameters
- `type`: News Type


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `lib.nua.edu.cn/:type/list.htm`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| News Type | Parameters |\n| --------- | ---------- |\n| 新闻动态  | xwdt       |\n| 党建动态  | djdt       |\n| 资源动态  | zydt       |\n| 服务动态  | fwdt       |",
  "example": "/nua/lib/xwdt",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "lib.ts",
  "maintainers": [
    "evnydd0sf"
  ],
  "name": "Library",
  "parameters": {
    "type": "News Type"
  },
  "path": "/lib/:type",
  "radar": [
    {
      "source": [
        "lib.nua.edu.cn/:type/list.htm"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at runNextTicks (node:internal/process/task_queues:69:3)\n    at listOnTimeout (node:internal/timers:567:9)\n    at processTimers (node:internal/timers:541:7)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "南京艺术学院 图书馆 新闻动态 - Powered by RSSHub",
      "errorAt": "2025-10-29T15:24:18.047Z",
      "errorMessage": "[GET] \"https://lib.nua.edu.cn/xwdt/list.htm\": <no response> fetch failed\n",
      "id": "75357267712093184",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://lib.nua.edu.cn/xwdt/list.htm",
      "title": "NUA-图书馆-新闻动态",
      "type": "feed",
      "url": "rsshub://nua/lib/xwdt"
    }
  ]
}
```
