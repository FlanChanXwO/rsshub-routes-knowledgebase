# 新语丝 - 新到资料

## Coverage
`index-only`

## Route
- Namespace: `xys`
- Namespace Name: `新语丝`
- Route Path: `/xys/new`
- Route Name: `新到资料`
- Example: `/xys/new`
- URL: `xys.org/`
- Language: `_None_`
- Categories: `blog`
- Maintainers: `wenzhenl`
- Source Location: `new.tsx`
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
  - `xys.org/`
  - `xys.org/new.html`

## Raw JSON
```json
{
  "categories": [
    "blog"
  ],
  "example": "/xys/new",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 76,
  "location": "new.tsx",
  "maintainers": [
    "wenzhenl"
  ],
  "name": "新到资料",
  "parameters": {},
  "path": "/new",
  "radar": [
    {
      "source": [
        "xys.org/",
        "xys.org/new.html"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected [ …(23) ] to not include 'https://www.youtube.com/channel/UCgTx…'\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.6/node_modules/@vitest/expect/dist/index.js:1319:15)\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.6/node_modules/@vitest/expect/dist/index.js:1156:15)\n    at Proxy.methodWrapper (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/chai@6.2.2/node_modules/chai/index.js:1700:25)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:67:27)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:82:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "新语丝 - 新到资料 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "57799650921358344",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://www.xys.org/new.html",
      "title": "新语丝 - 新到资料",
      "type": "feed",
      "url": "rsshub://xys/new"
    }
  ],
  "url": "xys.org/"
}
```
