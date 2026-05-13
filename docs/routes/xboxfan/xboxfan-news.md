# 盒心光环 - 资讯

## Coverage
`index-only`

## Route
- Namespace: `xboxfan`
- Namespace Name: `盒心光环`
- Route Path: `/xboxfan/news`
- Route Name: `资讯`
- Example: `/xboxfan/news`
- URL: `xboxfan.com/`
- Language: `_None_`
- Categories: `game`
- Maintainers: `XXY233`
- Source Location: `news.ts`
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
  - `xboxfan.com/`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "example": "/xboxfan/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 39,
  "location": "news.ts",
  "maintainers": [
    "XXY233"
  ],
  "name": "资讯",
  "parameters": {},
  "path": "/news",
  "radar": [
    {
      "source": [
        "xboxfan.com/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "盒心光环·资讯 - Powered by RSSHub",
      "errorAt": "2025-05-20T06:56:50.927Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "63019899021555712",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://xboxfan.com/",
      "title": "盒心光环·资讯",
      "type": "feed",
      "url": "rsshub://xboxfan/news"
    }
  ],
  "url": "xboxfan.com/"
}
```
