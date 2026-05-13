# 哔哩哔哩 bilibili - 视频弹幕

## Coverage
`index-only`

## Route
- Namespace: `bilibili`
- Namespace Name: `哔哩哔哩 bilibili`
- Route Path: `/bilibili/video/danmaku/:bvid/:pid?`
- Route Name: `视频弹幕`
- Example: `/bilibili/video/danmaku/BV1vA411b7ip/1`
- URL: `www.bilibili.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `Qixingchen`
- Source Location: `danmaku.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `bvid`: 视频AV号,可在视频页 URL 中找到
- `pid`: 分P号,不填默认为1


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
    "social-media"
  ],
  "example": "/bilibili/video/danmaku/BV1vA411b7ip/1",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "danmaku.ts",
  "maintainers": [
    "Qixingchen"
  ],
  "name": "视频弹幕",
  "parameters": {
    "bvid": "视频AV号,可在视频页 URL 中找到",
    "pid": "分P号,不填默认为1"
  },
  "path": "/video/danmaku/:bvid/:pid?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
