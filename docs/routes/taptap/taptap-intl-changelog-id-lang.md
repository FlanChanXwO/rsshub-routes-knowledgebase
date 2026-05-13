# TapTap - Game's Changelog

## Coverage
`index-only`

## Route
- Namespace: `taptap`
- Namespace Name: `TapTap`
- Route Path: `/taptap/intl/changelog/:id/:lang?`
- Route Name: `Game's Changelog`
- Example: `/taptap/intl/changelog/191001/zh_TW`
- URL: `www.taptap.io`
- Language: `_None_`
- Categories: `game`
- Maintainers: `hoilc, ETiV`
- Source Location: `changelog-intl.ts`
- Source Module: `_None_`

## Description
Language Code

| English (US) | 繁體中文 | 한국어 | 日本語 |
| ------------ | -------- | ------ | ------ |
| en\_US       | zh\_TW   | ko\_KR | ja\_JP |

## Parameters
- `id`: Game's App ID, you may find it from the URL of the Game
- `lang`: Language, checkout the table below for possible values, default is `en_US`


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
  - `www.taptap.io/app/:id`
- `target`: `/intl/changelog/:id`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "Language Code\n\n| English (US) | 繁體中文 | 한국어 | 日本語 |\n| ------------ | -------- | ------ | ------ |\n| en\\_US       | zh\\_TW   | ko\\_KR | ja\\_JP |",
  "example": "/taptap/intl/changelog/191001/zh_TW",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "changelog-intl.ts",
  "maintainers": [
    "hoilc",
    "ETiV"
  ],
  "name": "Game's Changelog",
  "parameters": {
    "id": "Game's App ID, you may find it from the URL of the Game",
    "lang": "Language, checkout the table below for possible values, default is `en_US`"
  },
  "path": "/intl/changelog/:id/:lang?",
  "radar": [
    {
      "source": [
        "www.taptap.io/app/:id"
      ],
      "target": "/intl/changelog/:id"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
