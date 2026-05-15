# 乳首ふぇち - Search

## Coverage
`index-only`

## Route
- Namespace: `chikubi`
- Namespace Name: `乳首ふぇち`
- Route Path: `/chikubi/search/:keyword`
- Route Name: `Search`
- Example: `/chikubi/search/ギャップ`
- URL: `chikubi.jp`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `SnowAgar25`
- Source Location: `search.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `keyword`: Keyword


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/chikubi/search/ギャップ",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 33,
  "location": "search.ts",
  "maintainers": [
    "SnowAgar25"
  ],
  "name": "Search",
  "parameters": {
    "keyword": "Keyword"
  },
  "path": "/search/:keyword",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 345522935597 to be less than 311040000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:38:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:63:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:82:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Search: 流出 - chikubi.jp - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "167795659806615552",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://chikubi.jp/search/%E6%B5%81%E5%87%BA",
      "title": "Search: 流出 - chikubi.jp",
      "type": "feed",
      "url": "rsshub://chikubi/search/%E6%B5%81%E5%87%BA"
    },
    {
      "description": "Search: ギャップ - chikubi.jp - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "67007423998717952",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://chikubi.jp/search/%E3%82%AE%E3%83%A3%E3%83%83%E3%83%97",
      "title": "Search: ギャップ - chikubi.jp",
      "type": "feed",
      "url": "rsshub://chikubi/search/%E3%82%AE%E3%83%A3%E3%83%83%E3%83%97"
    }
  ]
}
```
