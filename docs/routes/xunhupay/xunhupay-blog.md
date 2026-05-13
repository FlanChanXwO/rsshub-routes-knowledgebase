# 虎皮椒 - 文章

## Coverage
`index-only`

## Route
- Namespace: `xunhupay`
- Namespace Name: `虎皮椒`
- Route Path: `/xunhupay/blog`
- Route Name: `文章`
- Example: `/xunhupay/blog`
- URL: `www.xunhupay.com/blog`
- Language: `_None_`
- Categories: `blog`
- Maintainers: `Joey`
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
  - `www.xunhupay.com/blog`

## Raw JSON
```json
{
  "categories": [
    "blog"
  ],
  "example": "/xunhupay/blog",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "index.ts",
  "maintainers": [
    "Joey"
  ],
  "name": "文章",
  "parameters": {},
  "path": "/blog",
  "radar": [
    {
      "source": [
        "www.xunhupay.com/blog"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected [ 'JCgnYScpLmF0dHIoJ2hyZWYnKQ==' ] to not include 'JCgnYScpLmF0dHIoJ2hyZWYnKQ=='\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.6/node_modules/@vitest/expect/dist/index.js:1319:15)\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.6/node_modules/@vitest/expect/dist/index.js:1156:15)\n    at Proxy.methodWrapper (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/chai@6.2.2/node_modules/chai/index.js:1700:25)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:67:27)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:82:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "虎皮椒-博客 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "167568932496779264",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.xunhupay.com/blog.html",
      "title": "博客",
      "type": "feed",
      "url": "rsshub://xunhupay/blog"
    }
  ],
  "url": "www.xunhupay.com/blog"
}
```
