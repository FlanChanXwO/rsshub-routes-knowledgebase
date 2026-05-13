# Nintendo - Switch System Update（Japan）

## Coverage
`index-only`

## Route
- Namespace: `nintendo`
- Namespace Name: `Nintendo`
- Route Path: `/nintendo/system-update`
- Route Name: `Switch System Update（Japan）`
- Example: `/nintendo/system-update`
- URL: `nintendo.co.jp/support/switch/system_update/index.html`
- Language: `_None_`
- Categories: `game`
- Maintainers: `hoilc`
- Source Location: `system-update.ts`
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
  - `nintendo.co.jp/support/switch/system_update/index.html`
  - `nintendo.co.jp/`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "example": "/nintendo/system-update",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 13,
  "location": "system-update.ts",
  "maintainers": [
    "hoilc"
  ],
  "name": "Switch System Update（Japan）",
  "parameters": {},
  "path": "/system-update",
  "radar": [
    {
      "source": [
        "nintendo.co.jp/support/switch/system_update/index.html",
        "nintendo.co.jp/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected [ …(37) ] to not include 'https://www.nintendo.co.jp/support/sw…'\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.6/node_modules/@vitest/expect/dist/index.js:1319:15)\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.6/node_modules/@vitest/expect/dist/index.js:1156:15)\n    at Proxy.methodWrapper (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/chai@6.2.2/node_modules/chai/index.js:1700:25)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:67:27)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:82:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Nintendo Switch 本体更新情報 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "60263446472040455",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.nintendo.co.jp/support/switch/system_update/index.html",
      "title": "Nintendo Switch 本体更新情報",
      "type": "feed",
      "url": "rsshub://nintendo/system-update"
    }
  ],
  "url": "nintendo.co.jp/support/switch/system_update/index.html"
}
```
