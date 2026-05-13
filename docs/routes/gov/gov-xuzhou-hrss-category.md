# 上海市人民政府 - 徐州市人力资源和社会保障局

## Coverage
`index-only`

## Route
- Namespace: `gov`
- Namespace Name: `上海市人民政府`
- Route Path: `/gov/xuzhou/hrss/:category?`
- Route Name: `徐州市人力资源和社会保障局`
- Example: `/gov/xuzhou/hrss`
- URL: `sh.gov.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `nczitzk`
- Source Location: `xuzhou/hrss.ts`
- Source Module: `_None_`

## Description
| 通知公告 | 要闻动态 | 县区动态 | 事业招聘 | 企业招聘 | 政声传递 |
| -------- | -------- | -------- | -------- | -------- | -------- |
|          | 001001   | 001002   | 001004   | 001005   | 001006   |

## Parameters
- `category`: 分类，见下表，默认为通知公告


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
    "government"
  ],
  "description": "| 通知公告 | 要闻动态 | 县区动态 | 事业招聘 | 企业招聘 | 政声传递 |\n| -------- | -------- | -------- | -------- | -------- | -------- |\n|          | 001001   | 001002   | 001004   | 001005   | 001006   |",
  "example": "/gov/xuzhou/hrss",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "xuzhou/hrss.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "徐州市人力资源和社会保障局",
  "parameters": {
    "category": "分类，见下表，默认为通知公告"
  },
  "path": "/xuzhou/hrss/:category?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
