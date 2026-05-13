# 虫部落 - 最新发表

## Coverage
`index-only`

## Route
- Namespace: `chongbuluo`
- Namespace Name: `虫部落`
- Route Path: `/chongbuluo/newthread`
- Route Name: `最新发表`
- Example: `/chongbuluo/newthread`
- URL: `www.chongbuluo.com`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `qiye45`
- Source Location: `index.ts`
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
  - `www.chongbuluo.com/`

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "example": "/chongbuluo/newthread",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 102,
  "location": "index.ts",
  "maintainers": [
    "qiye45"
  ],
  "name": "最新发表",
  "path": "/newthread",
  "radar": [
    {
      "source": [
        "www.chongbuluo.com/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "虫部落最新发表的帖子 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "144338273329964032",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.chongbuluo.com/forum.php?mod=guide&view=newthread",
      "title": "虫部落 - 最新发表",
      "type": "feed",
      "url": "rsshub://chongbuluo/newthread"
    }
  ]
}
```
