# 软餐 - 分类

## Coverage
`index-only`

## Route
- Namespace: `ruancan`
- Namespace Name: `软餐`
- Route Path: `/ruancan/category/:category?`
- Route Name: `分类`
- Example: `/ruancan/category/news`
- URL: `ruancan.com/`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `None`
- Source Location: `category.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `category`: 分类 id，可在对应分类页 URL 中找到，默认为业界


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
  - `ruancan.com/cat/:category`
  - `ruancan.com/`
- `target`: `/category/:category`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/ruancan/category/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "category.ts",
  "maintainers": [],
  "name": "分类",
  "parameters": {
    "category": "分类 id，可在对应分类页 URL 中找到，默认为业界"
  },
  "path": "/category/:category?",
  "radar": [
    {
      "source": [
        "ruancan.com/cat/:category",
        "ruancan.com/"
      ],
      "target": "/category/:category"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "ruancan.com/"
}
```
