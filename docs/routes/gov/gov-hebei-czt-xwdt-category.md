# 深圳市罗湖区人民政府 - 财政厅

## Coverage
`index-only`

## Route
- Namespace: `gov`
- Namespace Name: `深圳市罗湖区人民政府`
- Route Path: `/gov/hebei/czt/xwdt/:category?`
- Route Name: `财政厅`
- Example: `/gov/hebei/czt/xwdt`
- URL: `www.szlh.gov.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `nczitzk`
- Source Location: `hebei/czt.ts`
- Source Module: `_None_`

## Description
| 财政动态 | 综合新闻 | 通知公告 |
| -------- | -------- | -------- |
| gzdt     | zhxw     | tzgg     |

## Parameters
- `category`: 分类，见下表，默认为财政动态


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
  "description": "| 财政动态 | 综合新闻 | 通知公告 |\n| -------- | -------- | -------- |\n| gzdt     | zhxw     | tzgg     |",
  "example": "/gov/hebei/czt/xwdt",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "hebei/czt.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "财政厅",
  "parameters": {
    "category": "分类，见下表，默认为财政动态"
  },
  "path": "/hebei/czt/xwdt/:category?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
