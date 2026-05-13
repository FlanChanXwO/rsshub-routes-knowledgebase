# 中国人民银行 - 申请事项进度

## Coverage
`index-only`

## Route
- Namespace: `gov`
- Namespace Name: `中国人民银行`
- Route Path: `/gov/csrc/auditstatus/:apply_id`
- Route Name: `申请事项进度`
- Example: `/gov/csrc/auditstatus/9ce91cf2d750ee62de27fbbcb05fa483`
- URL: `pbc.gov.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `hillerliao`
- Source Location: `csrc/auditstatus.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `apply_id`: 事项类别id，`https://neris.csrc.gov.cn/alappl/home/xkDetail` 列表中各地址的 appMatrCde 参数


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
  "example": "/gov/csrc/auditstatus/9ce91cf2d750ee62de27fbbcb05fa483",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "csrc/auditstatus.ts",
  "maintainers": [
    "hillerliao"
  ],
  "name": "申请事项进度",
  "parameters": {
    "apply_id": "事项类别id，`https://neris.csrc.gov.cn/alappl/home/xkDetail` 列表中各地址的 appMatrCde 参数"
  },
  "path": "/csrc/auditstatus/:apply_id",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
