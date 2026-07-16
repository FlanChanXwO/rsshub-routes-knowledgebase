# 豆瓣 - 热门同城活动

## Coverage
`index-only`

## Route
- Namespace: `douban`
- Namespace Name: `豆瓣`
- Route Path: `/douban/event/hot/:locationId`
- Route Name: `热门同城活动`
- Example: `/douban/event/hot/118172`
- URL: `www.douban.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `xyqfer`
- Source Location: `event/hot.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `locationId`: 位置 id, [同城首页](https://www.douban.com/location)打开控制台执行 `window.__loc_id__` 获取


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
  "example": "/douban/event/hot/118172",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 30,
  "location": "event/hot.ts",
  "maintainers": [
    "xyqfer"
  ],
  "name": "热门同城活动",
  "parameters": {
    "locationId": "位置 id, [同城首页](https://www.douban.com/location)打开控制台执行 `window.__loc_id__` 获取"
  },
  "path": "/event/hot/:locationId",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "豆瓣同城-热门活动-108288 - Powered by RSSHub",
      "errorAt": "2026-07-15T05:19:02.839Z",
      "errorMessage": "Failed to fetch\n",
      "id": "66737530237513737",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://m.douban.com/app_topic/event_hot",
      "title": "豆瓣同城-热门活动-108288",
      "type": "feed",
      "url": "rsshub://douban/event/hot/108288"
    },
    {
      "description": "豆瓣同城-热门活动-108296 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "72575419585855536",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://m.douban.com/app_topic/event_hot",
      "title": "豆瓣同城-热门活动-108296",
      "type": "feed",
      "url": "rsshub://douban/event/hot/108296"
    }
  ]
}
```
