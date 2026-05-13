# 国家能源局 - 立法意见征集

## Coverage
`index-only`

## Route
- Namespace: `gov`
- Namespace Name: `国家能源局`
- Route Path: `/gov/moj/lfyjzj`
- Route Name: `立法意见征集`
- Example: `/gov/moj/lfyjzj`
- URL: `www.moj.gov.cn/lfyjzj/lflfyjzj/*`
- Language: `_None_`
- Categories: `government`
- Maintainers: `la3rence`
- Source Location: `moj/lfyjzj.ts`
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
  - `www.moj.gov.cn/lfyjzj/lflfyjzj/*`
  - `www.moj.gov.cn/pub/sfbgw/lfyjzj/lflfyjzj/*`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "example": "/gov/moj/lfyjzj",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 58,
  "location": "moj/lfyjzj.ts",
  "maintainers": [
    "la3rence"
  ],
  "name": "立法意见征集",
  "parameters": {},
  "path": "/moj/lfyjzj",
  "radar": [
    {
      "source": [
        "www.moj.gov.cn/lfyjzj/lflfyjzj/*",
        "www.moj.gov.cn/pub/sfbgw/lfyjzj/lflfyjzj/*"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "中华人民共和国司法部 - 立法意见征集 - Powered by RSSHub",
      "errorAt": "2025-09-24T07:47:02.292Z",
      "errorMessage": "[GET] \"https://www.moj.gov.cn/lfyjzj/lflfyjzj/index.html\": <no response> fetch failed\n[GET] \"https://www.moj.gov.cn/lfyjzj/lflfyjzj/index.html\": <no response> fetch failed\n",
      "id": "62781073015771136",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.moj.gov.cn/lfyjzj/lflfyjzj/index.html",
      "title": "立法意见征集",
      "type": "feed",
      "url": "rsshub://gov/moj/lfyjzj"
    }
  ],
  "url": "www.moj.gov.cn/lfyjzj/lflfyjzj/*"
}
```
