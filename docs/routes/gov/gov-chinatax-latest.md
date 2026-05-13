# 国家能源局 - 最新文件

## Coverage
`index-only`

## Route
- Namespace: `gov`
- Namespace Name: `国家能源局`
- Route Path: `/gov/chinatax/latest`
- Route Name: `最新文件`
- Example: `/gov/chinatax/latest`
- URL: `www.chinatax.gov.cn/*`
- Language: `_None_`
- Categories: `government`
- Maintainers: `nczitzk, fuzy112`
- Source Location: `chinatax/latest.ts`
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
  - `www.chinatax.gov.cn/*`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "example": "/gov/chinatax/latest",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1179,
  "location": "chinatax/latest.ts",
  "maintainers": [
    "nczitzk",
    "fuzy112"
  ],
  "name": "最新文件",
  "parameters": {},
  "path": "/chinatax/latest",
  "radar": [
    {
      "source": [
        "www.chinatax.gov.cn/*"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "国家税务总局 - 最新文件 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "62722084868717571",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://www.chinatax.gov.cn/chinatax/n810341/n810755/index.html",
      "title": "国家税务总局 - 最新文件",
      "type": "feed",
      "url": "rsshub://gov/chinatax/latest"
    }
  ],
  "url": "www.chinatax.gov.cn/*"
}
```
