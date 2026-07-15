# 猫眼电影 - 正在热映

## Coverage
`index-only`

## Route
- Namespace: `maoyan`
- Namespace Name: `猫眼电影`
- Route Path: `/maoyan/hot`
- Route Name: `正在热映`
- Example: `/maoyan/hot`
- URL: `maoyan.com`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `JackyST0`
- Source Location: `hot.ts`
- Source Module: `_None_`

## Description
_None_

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
### Rule 1
- `source`:
  - `www.maoyan.com/films?showType=1`
- `target`: `/hot`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/maoyan/hot",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 13,
  "location": "hot.ts",
  "maintainers": [
    "JackyST0"
  ],
  "name": "正在热映",
  "parameters": {},
  "path": "/hot",
  "radar": [
    {
      "source": [
        "www.maoyan.com/films?showType=1"
      ],
      "target": "/hot"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "猫眼电影正在热映列表 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "148757739569766403",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.maoyan.com/films?showType=1",
      "title": "猫眼电影 - 正在热映",
      "type": "feed",
      "url": "rsshub://maoyan/hot"
    }
  ]
}
```
