# 人人影视 - 今日播出

## Coverage
`index-only`

## Route
- Namespace: `yyets`
- Namespace Name: `人人影视`
- Route Path: `/yyets/today`
- Route Name: `今日播出`
- Example: `/yyets/today`
- URL: `yysub.net/tv/schedule`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `bao1991213`
- Source Location: `today.ts`
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
  - `yysub.net/tv/schedule`
  - `yysub.net/`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/yyets/today",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 840,
  "location": "today.ts",
  "maintainers": [
    "bao1991213"
  ],
  "name": "今日播出",
  "parameters": {},
  "path": "/today",
  "radar": [
    {
      "source": [
        "yysub.net/tv/schedule",
        "yysub.net/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "人人影视-今日播出 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "58488203296243712",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://yysub.net/",
      "title": "人人影视-今日播出",
      "type": "feed",
      "url": "rsshub://yyets/today"
    }
  ],
  "url": "yysub.net/tv/schedule",
  "view": 5
}
```
