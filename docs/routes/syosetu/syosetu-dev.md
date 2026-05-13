# Syosetu - なろう小説 API の更新履歴

## Coverage
`index-only`

## Route
- Namespace: `syosetu`
- Namespace Name: `Syosetu`
- Route Path: `/syosetu/dev`
- Route Name: `なろう小説 API の更新履歴`
- Example: `/syosetu/dev`
- URL: `dev.syosetu.com`
- Language: `_None_`
- Categories: `program-update`
- Maintainers: `SnowAgar25`
- Source Location: `dev.ts`
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
- `title`: `なろう小説 API の更新履歴`
- `source`:
  - `dev.syosetu.com`
- `target`: `/dev`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "example": "/syosetu/dev",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "dev.ts",
  "maintainers": [
    "SnowAgar25"
  ],
  "name": "なろう小説 API の更新履歴",
  "path": "/dev",
  "radar": [
    {
      "source": [
        "dev.syosetu.com"
      ],
      "target": "/dev",
      "title": "なろう小説 API の更新履歴"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 314591055502 to be less than 311040000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:38:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:63:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:82:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "dev.syosetu.com"
}
```
