# 雪球 - 热帖

## Coverage
`index-only`

## Route
- Namespace: `xueqiu`
- Namespace Name: `雪球`
- Route Path: `/xueqiu/hots`
- Route Name: `热帖`
- Example: `/xueqiu/hots`
- URL: `xueqiu.com/`
- Language: `_None_`
- Categories: `finance, popular`
- Maintainers: `hillerliao`
- Source Location: `hots.ts`
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
  - `xueqiu.com/`

## Raw JSON
```json
{
  "categories": [
    "finance",
    "popular"
  ],
  "example": "/xueqiu/hots",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 3543,
  "location": "hots.ts",
  "maintainers": [
    "hillerliao"
  ],
  "name": "热帖",
  "parameters": {},
  "path": "/hots",
  "radar": [
    {
      "source": [
        "xueqiu.com/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "雪球热门帖子 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "53033422584152064",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://xueqiu.com/",
      "title": "热帖 - 雪球",
      "type": "feed",
      "url": "rsshub://xueqiu/hots"
    }
  ],
  "url": "xueqiu.com/"
}
```
