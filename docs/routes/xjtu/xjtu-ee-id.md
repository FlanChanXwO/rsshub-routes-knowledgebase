# 西安交通大学 - 电气学院

## Coverage
`index-only`

## Route
- Namespace: `xjtu`
- Namespace Name: `西安交通大学`
- Route Path: `/xjtu/ee/:id?`
- Route Name: `电气学院`
- Example: `/xjtu/ee/1114`
- URL: `ee.xjtu.edu.cn/`
- Language: `_None_`
- Categories: `university`
- Maintainers: `DylanXie123`
- Source Location: `ee.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 栏目id，默认请求`1124`，可在 URL 中找到


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
  - `ee.xjtu.edu.cn/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/xjtu/ee/1114",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "ee.ts",
  "maintainers": [
    "DylanXie123"
  ],
  "name": "电气学院",
  "parameters": {
    "id": "栏目id，默认请求`1124`，可在 URL 中找到"
  },
  "path": "/ee/:id?",
  "radar": [
    {
      "source": [
        "ee.xjtu.edu.cn/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "ee.xjtu.edu.cn/"
}
```
