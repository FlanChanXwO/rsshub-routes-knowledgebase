# 武汉大学 - 水利水电学院公告

## Coverage
`index-only`

## Route
- Namespace: `whu`
- Namespace Name: `武汉大学`
- Route Path: `/whu/swrh/:type`
- Route Name: `水利水电学院公告`
- Example: `/whu/swrh/2`
- URL: `cs.whu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `FanofZY`
- Source Location: `swrh.ts`
- Source Module: `_None_`

## Description
| 公告类型 | 学院新闻 | 学术科研 | 通知公告 |
| -------- | -------- | -------- | -------- |
| 参数     | 0        | 1        | 2        |

## Parameters
- `type`: 公告类型，详见表格


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
  - `swrh.whu.edu.cn/:type`
- `target`: `/swrh/:type`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 公告类型 | 学院新闻 | 学术科研 | 通知公告 |\n| -------- | -------- | -------- | -------- |\n| 参数     | 0        | 1        | 2        |",
  "example": "/whu/swrh/2",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "swrh.ts",
  "maintainers": [
    "FanofZY"
  ],
  "name": "水利水电学院公告",
  "parameters": {
    "type": "公告类型，详见表格"
  },
  "path": "/swrh/:type",
  "radar": [
    {
      "source": [
        "swrh.whu.edu.cn/:type"
      ],
      "target": "/swrh/:type"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
