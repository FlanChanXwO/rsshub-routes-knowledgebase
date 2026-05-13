# 雪球 - 今日话题

## Coverage
`index-only`

## Route
- Namespace: `xueqiu`
- Namespace Name: `雪球`
- Route Path: `/xueqiu/today`
- Route Name: `今日话题`
- Example: `/xueqiu/today`
- URL: `xueqiu.com/today`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `nczitzk`
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
  - `xueqiu.com/today`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/xueqiu/today",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 210,
  "location": "today.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "今日话题",
  "parameters": {},
  "path": "/today",
  "radar": [
    {
      "source": [
        "xueqiu.com/today"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "今日话题 - 雪球 - Powered by RSSHub",
      "errorAt": "2025-11-09T14:35:43.859Z",
      "errorMessage": "Failed to fetch\nCannot read properties of undefined (reading 'map')\n",
      "id": "61288440756878338",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://xueqiu.com/today",
      "title": "今日话题 - 雪球",
      "type": "feed",
      "url": "rsshub://xueqiu/today"
    }
  ],
  "url": "xueqiu.com/today"
}
```
