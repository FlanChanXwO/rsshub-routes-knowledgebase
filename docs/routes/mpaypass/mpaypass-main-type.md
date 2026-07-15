# 移动支付网 - 分类

## Coverage
`index-only`

## Route
- Namespace: `mpaypass`
- Namespace Name: `移动支付网`
- Route Path: `/mpaypass/main/:type?`
- Route Name: `分类`
- Example: `/mpaypass/main/policy`
- URL: `mpaypass.com.cn`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `zhuan-zhu`
- Source Location: `main.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `type`: 新闻类型，类型可在URL中找到，类似`policy`，`eye`等，空或其他任意值展示最新新闻


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
    "new-media"
  ],
  "example": "/mpaypass/main/policy",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "main.ts",
  "maintainers": [
    "zhuan-zhu"
  ],
  "name": "分类",
  "parameters": {
    "type": "新闻类型，类型可在URL中找到，类似`policy`，`eye`等，空或其他任意值展示最新新闻"
  },
  "path": "/main/:type?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
