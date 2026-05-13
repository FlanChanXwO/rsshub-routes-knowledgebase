# 澎湃新闻 - 政务号

## Coverage
`index-only`

## Route
- Namespace: `thepaper`
- Namespace Name: `澎湃新闻`
- Route Path: `/thepaper/gov/:pphId`
- Route Name: `政务号`
- Example: `/thepaper/gov/63850`
- URL: `thepaper.cn`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `occam-7`
- Source Location: `gov.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `pphId`: 政务号 id，可在政务号页 URL 中找到


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
  "example": "/thepaper/gov/63850",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "gov.ts",
  "maintainers": [
    "occam-7"
  ],
  "name": "政务号",
  "parameters": {
    "pphId": "政务号 id，可在政务号页 URL 中找到"
  },
  "path": "/gov/:pphId",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
