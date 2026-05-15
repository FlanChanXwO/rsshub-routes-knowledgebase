# U3C3 - Search

## Coverage
`index-only`

## Route
- Namespace: `u3c3`
- Namespace Name: `U3C3`
- Route Path: `/u3c3/search/:keyword/:preview?`
- Route Name: `Search`
- Example: `/u3c3/search/新片速递`
- URL: `u3c3.com`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `storytellerF`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `keyword`: Search keyword
- `preview`: Show image preview, off by default, non empty value means on


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: true
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/u3c3/search/新片速递",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": true,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 47,
  "location": "index.ts",
  "maintainers": [
    "storytellerF"
  ],
  "name": "Search",
  "parameters": {
    "keyword": "Search keyword",
    "preview": "Show image preview, off by default, non empty value means on"
  },
  "path": [
    "/search/:keyword/:preview?",
    "/:type?/:preview?"
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected -2297337858278 to be greater than -432000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:37:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:63:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:82:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "home - u3c3 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "68549075258311680",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.u3c3.com/",
      "title": "home - u3c3",
      "type": "feed",
      "url": "rsshub://u3c3/search/%E6%96%B0%E7%89%87%E9%80%9F%E9%80%92"
    },
    {
      "description": "home - u3c3 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "131696291531404288",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.u3c3.com/",
      "title": "home - u3c3",
      "type": "feed",
      "url": "rsshub://u3c3/search/U3C3"
    }
  ]
}
```
