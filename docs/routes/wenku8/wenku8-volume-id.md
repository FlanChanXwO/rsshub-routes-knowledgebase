# 轻小说文库 - 最新卷

## Coverage
`index-only`

## Route
- Namespace: `wenku8`
- Namespace Name: `轻小说文库`
- Route Path: `/wenku8/volume/:id`
- Route Name: `最新卷`
- Example: `/wenku8/volume/1163`
- URL: `www.wenku8.net`
- Language: `_None_`
- Categories: `reading`
- Maintainers: `huangliangshusheng`
- Source Location: `volume.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 小说 id, 可在对应小说页 URL 中找到


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
    "reading"
  ],
  "example": "/wenku8/volume/1163",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "volume.ts",
  "maintainers": [
    "huangliangshusheng"
  ],
  "name": "最新卷",
  "parameters": {
    "id": "小说 id, 可在对应小说页 URL 中找到"
  },
  "path": "/volume/:id",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
