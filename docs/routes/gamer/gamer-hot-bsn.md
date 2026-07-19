# 巴哈姆特電玩資訊站 - 本板推薦

## Coverage
`index-only`

## Route
- Namespace: `gamer`
- Namespace Name: `巴哈姆特電玩資訊站`
- Route Path: `/gamer/hot/:bsn`
- Route Name: `本板推薦`
- Example: `/gamer/hot/47157`
- URL: `acg.gamer.com.tw`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `nczitzk, TonyRL, kennyfong19931`
- Source Location: `hot.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `bsn`: 板塊 id，在 URL 可以找到


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/gamer/hot/47157",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 69,
  "location": "hot.ts",
  "maintainers": [
    "nczitzk",
    "TonyRL",
    "kennyfong19931"
  ],
  "name": "本板推薦",
  "parameters": {
    "bsn": "板塊 id，在 URL 可以找到"
  },
  "path": "/hot/:bsn",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "星期一的豐滿 哈啦板 - 巴哈姆特 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "61362528816905216",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://forum.gamer.com.tw/B.php?bsn=47157",
      "title": "星期一的豐滿 哈啦板 - 巴哈姆特",
      "type": "feed",
      "url": "rsshub://gamer/hot/47157"
    },
    {
      "description": "電腦應用綜合討論 哈啦板 - 巴哈姆特 - Powered by RSSHub",
      "errorAt": "2026-07-18T05:54:29.689Z",
      "errorMessage": "[GET] \"https://forum.gamer.com.tw/B.php?bsn=60030\": 403 Forbidden\n",
      "id": "81271469008480256",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://forum.gamer.com.tw/B.php?bsn=60030",
      "title": "電腦應用綜合討論 哈啦板 - 巴哈姆特",
      "type": "feed",
      "url": "rsshub://gamer/hot/60030"
    }
  ],
  "view": 0
}
```
