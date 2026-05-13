# 清华大学 - 图书馆通知公告

## Coverage
`index-only`

## Route
- Namespace: `tsinghua`
- Namespace Name: `清华大学`
- Route Path: `/tsinghua/lib/tzgg/:category`
- Route Name: `图书馆通知公告`
- Example: `/tsinghua/lib/tzgg/qtkx`
- URL: `tsinghua.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `linsenwang`
- Source Location: `lib/tzgg.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `category`: 分类，可在对应分类页 URL 中找到


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
  - `lib.tsinghua.edu.cn/tzgg/:category`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/tsinghua/lib/tzgg/qtkx",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "lib/tzgg.ts",
  "maintainers": [
    "linsenwang"
  ],
  "name": "图书馆通知公告",
  "parameters": {
    "category": "分类，可在对应分类页 URL 中找到"
  },
  "path": "/lib/tzgg/:category",
  "radar": [
    {
      "source": [
        "lib.tsinghua.edu.cn/tzgg/:category"
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
