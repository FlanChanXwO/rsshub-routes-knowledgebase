# Meteor - 看板列表

## Coverage
`index-only`

## Route
- Namespace: `meteor`
- Namespace Name: `Meteor`
- Route Path: `/meteor/boards`
- Route Name: `看板列表`
- Example: `/meteor/boards`
- URL: `meteor.today/`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `TonyRL`
- Source Location: `boards.ts`
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
  - `meteor.today/`

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "example": "/meteor/boards",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 2,
  "location": "boards.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "看板列表",
  "parameters": {},
  "path": "/boards",
  "radar": [
    {
      "source": [
        "meteor.today/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected [ …(308) ] to not include 'https://meteor.today/board/%E5%BD%B0%…'\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.6/node_modules/@vitest/expect/dist/index.js:1319:15)\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.6/node_modules/@vitest/expect/dist/index.js:1156:15)\n    at Proxy.methodWrapper (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/chai@6.2.2/node_modules/chai/index.js:1700:25)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:67:27)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:82:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "看板列表 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "86117617623281664",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://meteor.today/board/all",
      "title": "看板列表",
      "type": "feed",
      "url": "rsshub://meteor/boards"
    }
  ],
  "url": "meteor.today/"
}
```
