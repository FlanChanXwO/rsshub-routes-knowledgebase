# 紳士漫畫 - 分类更新

## Coverage
`index-only`

## Route
- Namespace: `wnacg`
- Namespace Name: `紳士漫畫`
- Route Path: `/wnacg/category/:cid`
- Route Name: `分类更新`
- Example: `/wnacg/category/6`
- URL: `wnacg.com/albums.html`
- Language: `_None_`
- Categories: `other`
- Maintainers: `Gandum2077`
- Source Location: `category.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


## Features
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `wnacg.com/*`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "example": "/wnacg/category/6",
  "features": {
    "nsfw": true
  },
  "heat": 600,
  "location": "category.ts",
  "maintainers": [
    "Gandum2077"
  ],
  "name": "分类更新",
  "path": "/category/:cid",
  "radar": [
    {
      "source": [
        "wnacg.com/*"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected -59865885136 to be greater than -432000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:37:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:63:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:82:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "漢化 < 雜誌&短篇 < 紳士漫畫-專註分享漢化本子|邪惡漫畫 - Powered by RSSHub",
      "errorAt": "2026-05-13T03:05:33.560Z",
      "errorMessage": "Failed query: select \"id\", \"guid\", \"media\" from \"entries\" \"entries\" where \"entries\".\"feed_id\" = $1\nparams: 42178678837350400",
      "id": "42178678837350400",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.wnacg.com/albums-index-cate-10.html",
      "title": "漢化 < 雜誌&短篇 < 紳士漫畫-專註分享漢化本子|邪惡漫畫",
      "type": "feed",
      "url": "rsshub://wnacg/category/10"
    },
    {
      "description": "寫真&Cosplay < 紳士漫畫-專註分享漢化本子|邪惡漫畫 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "70519954758300672",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.wnacg.com/albums-index-cate-3.html",
      "title": "寫真&Cosplay < 紳士漫畫-專註分享漢化本子|邪惡漫畫",
      "type": "feed",
      "url": "rsshub://wnacg/category/3"
    }
  ],
  "url": "wnacg.com/albums.html"
}
```
