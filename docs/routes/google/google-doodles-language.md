# Google - Update

## Coverage
`index-only`

## Route
- Namespace: `google`
- Namespace Name: `Google`
- Route Path: `/google/doodles/:language?`
- Route Name: `Update`
- Example: `/google/doodles/zh-CN`
- URL: `www.google.com`
- Language: `_None_`
- Categories: `picture`
- Maintainers: `xyqfer`
- Source Location: `doodles.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `language`: Language, default to `zh-CN`, for other language values, you can get it from [Google Doodles official website](https://www.google.com/doodles)


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
    "picture"
  ],
  "example": "/google/doodles/zh-CN",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 372,
  "location": "doodles.ts",
  "maintainers": [
    "xyqfer"
  ],
  "name": "Update",
  "parameters": {
    "language": "Language, default to `zh-CN`, for other language values, you can get it from [Google Doodles official website](https://www.google.com/doodles)"
  },
  "path": "/doodles/:language?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Google Doodles - Powered by RSSHub",
      "errorAt": "2025-05-02T15:53:49.300Z",
      "errorMessage": "[GET] \"https://www.google.com/doodles/json/2026/5?hl=zh-CN\": 404 Not Found\n[GET] \"https://www.google.com/doodles/json/2026/5?hl=zh-CN\": 404 Not Found\n",
      "id": "64590393280128000",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.google.com/doodles?hl=zh-CN",
      "title": "Google Doodles",
      "type": "feed",
      "url": "rsshub://google/doodles"
    },
    {
      "description": "Google Doodles - Powered by RSSHub",
      "errorAt": "2025-05-02T22:52:17.568Z",
      "errorMessage": "[GET] \"https://www.google.com/doodles/json/2026/5?hl=zh-CN\": 404 Not Found\n",
      "id": "57366193674068992",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.google.com/doodles?hl=zh-CN",
      "title": "Google Doodles",
      "type": "feed",
      "url": "rsshub://google/doodles/zh-CN"
    }
  ],
  "view": 2
}
```
