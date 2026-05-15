# 深圳市罗湖区人民政府 - 省科学技术厅

## Coverage
`index-only`

## Route
- Namespace: `gov`
- Namespace Name: `深圳市罗湖区人民政府`
- Route Path: `/gov/shaanxi/kjt/:id?`
- Route Name: `省科学技术厅`
- Example: `/gov/shaanxi/kjt`
- URL: `www.szlh.gov.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `nczitzk`
- Source Location: `shaanxi/kjt.ts`
- Source Module: `_None_`

## Description
| 科技头条 | 工作动态 | 基层科技 | 科技博览 | 媒体聚焦 | 通知公告 |
| -------- | -------- | -------- | -------- | -------- | -------- |
| 1061     | 24       | 27       | 25       | 28       | 221      |

## Parameters
- `id`: 分类，见下表，默认为通知公告


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
  "description": "| 科技头条 | 工作动态 | 基层科技 | 科技博览 | 媒体聚焦 | 通知公告 |\n| -------- | -------- | -------- | -------- | -------- | -------- |\n| 1061     | 24       | 27       | 25       | 28       | 221      |",
  "example": "/gov/shaanxi/kjt",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "shaanxi/kjt.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "省科学技术厅",
  "parameters": {
    "id": "分类，见下表，默认为通知公告"
  },
  "path": "/shaanxi/kjt/:id?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
