# 哔哩哔哩 bilibili - 热搜

## Coverage
`index-only`

## Route
- Namespace: `bilibili`
- Namespace Name: `哔哩哔哩 bilibili`
- Route Path: `/bilibili/hot-search`
- Route Name: `热搜`
- Example: `/bilibili/hot-search`
- URL: `www.bilibili.com/`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `CaoMeiYouRen`
- Source Location: `hot-search.ts`
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
  - `www.bilibili.com/`
### Rule 2
- `source`:
  - `m.bilibili.com/`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/bilibili/hot-search",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 278,
  "location": "hot-search.ts",
  "maintainers": [
    "CaoMeiYouRen"
  ],
  "name": "热搜",
  "parameters": {},
  "path": "/hot-search",
  "radar": [
    {
      "source": [
        "www.bilibili.com/"
      ]
    },
    {
      "source": [
        "m.bilibili.com/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "bilibili热搜 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "54831663495804928",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://api.bilibili.com/x/web-interface/wbi/search/square?limit=10&platform=web&w_rid=80b282c66e7a7de26c686837396351aa&wts=1778725269",
      "title": "bilibili热搜",
      "type": "feed",
      "url": "rsshub://bilibili/hot-search"
    }
  ],
  "url": "www.bilibili.com/"
}
```
