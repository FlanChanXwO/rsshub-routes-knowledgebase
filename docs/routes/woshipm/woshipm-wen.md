# 人人都是产品经理 - 天天问

## Coverage
`index-only`

## Route
- Namespace: `woshipm`
- Namespace Name: `人人都是产品经理`
- Route Path: `/woshipm/wen`
- Route Name: `天天问`
- Example: `/woshipm/wen`
- URL: `wen.woshipm.com/`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `WenryXu`
- Source Location: `wen.ts`
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
  - `wen.woshipm.com/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/woshipm/wen",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 15,
  "location": "wen.ts",
  "maintainers": [
    "WenryXu"
  ],
  "name": "天天问",
  "parameters": {},
  "path": "/wen",
  "radar": [
    {
      "source": [
        "wen.woshipm.com/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected NaN to be greater than -432000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:37:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:63:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:82:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "天天问 - 人人都是产品经理 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "67443723163710464",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://wen.woshipm.com/",
      "title": "天天问 - 人人都是产品经理",
      "type": "feed",
      "url": "rsshub://woshipm/wen"
    }
  ],
  "url": "wen.woshipm.com/"
}
```
