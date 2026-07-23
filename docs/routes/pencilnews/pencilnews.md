# 铅笔道 - 文章列表

## Coverage
`index-only`

## Route
- Namespace: `pencilnews`
- Namespace Name: `铅笔道`
- Route Path: `/pencilnews/`
- Route Name: `文章列表`
- Example: `/pencilnews`
- URL: `www.pencilnews.cn`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `defp`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
获取铅笔道最新文章

## Parameters
_None_


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
  "description": "获取铅笔道最新文章",
  "example": "/pencilnews",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "defp"
  ],
  "name": "文章列表",
  "parameters": {},
  "path": "/",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
