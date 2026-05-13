# 旅法师营地 - 首页（旧版）

## Coverage
`index-only`

## Route
- Namespace: `lfsyd`
- Namespace Name: `旅法师营地`
- Route Path: `/lfsyd/old_home`
- Route Name: `首页（旧版）`
- Example: `/lfsyd/old_home`
- URL: `www.iyingdi.com/`
- Language: `_None_`
- Categories: `game`
- Maintainers: `auto-bot-ty`
- Source Location: `old-home.ts`
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
  - `www.iyingdi.com/`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "example": "/lfsyd/old_home",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "old-home.ts",
  "maintainers": [
    "auto-bot-ty"
  ],
  "name": "首页（旧版）",
  "parameters": {},
  "path": "/old_home",
  "radar": [
    {
      "source": [
        "www.iyingdi.com/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "旅法师营地 - 首页资讯（旧版） - Powered by RSSHub",
      "errorAt": "2025-11-21T15:02:32.639Z",
      "errorMessage": "[GET] \"https://www.iyingdi.com/feed/list/user/v3?feedIdUp=0&feedIdDown=0&hotfeed=1&system=web\": 404 Not Found\n",
      "id": "41840596114310144",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.iyingdi.com/",
      "title": "旅法师营地 - 首页资讯（旧版）",
      "type": "feed",
      "url": "rsshub://lfsyd/old_home"
    }
  ],
  "url": "www.iyingdi.com/"
}
```
