# 南方周末 - 热门文章

## Coverage
`index-only`

## Route
- Namespace: `infzm`
- Namespace Name: `南方周末`
- Route Path: `/infzm/hot`
- Route Name: `热门文章`
- Example: `/infzm/hot`
- URL: `www.infzm.com`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `KarasuShin, ranpox, xyqfer`
- Source Location: `hot.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `infzm.com/`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/infzm/hot",
  "heat": 397,
  "location": "hot.ts",
  "maintainers": [
    "KarasuShin",
    "ranpox",
    "xyqfer"
  ],
  "name": "热门文章",
  "parameters": {},
  "path": "/hot",
  "radar": [
    {
      "source": [
        "infzm.com/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "南方周末-热门文章 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "62790413740228608",
      "image": "https://www.infzm.com/favicon.ico",
      "ownerUserId": null,
      "siteUrl": "https://www.infzm.com/",
      "title": "南方周末-热门文章",
      "type": "feed",
      "url": "rsshub://infzm/hot"
    }
  ]
}
```
