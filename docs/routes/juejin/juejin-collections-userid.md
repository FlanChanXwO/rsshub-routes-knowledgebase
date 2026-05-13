# 掘金 - 收藏集

## Coverage
`index-only`

## Route
- Namespace: `juejin`
- Namespace Name: `掘金`
- Route Path: `/juejin/collections/:userId`
- Route Name: `收藏集`
- Example: `/juejin/collections/1697301682482439`
- URL: `juejin.cn`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `yang131323`
- Source Location: `collections.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `userId`: 用户唯一标志符, 在浏览器地址栏URL中能够找到


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
  - `juejin.cn/user/:id`
  - `juejin.cn/user/:id/collections`
- `target`: `/collections/:id`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/juejin/collections/1697301682482439",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 9,
  "location": "collections.ts",
  "maintainers": [
    "yang131323"
  ],
  "name": "收藏集",
  "parameters": {
    "userId": "用户唯一标志符, 在浏览器地址栏URL中能够找到"
  },
  "path": "/collections/:userId",
  "radar": [
    {
      "source": [
        "juejin.cn/user/:id",
        "juejin.cn/user/:id/collections"
      ],
      "target": "/collections/:id"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "掘金，指定用户整个收藏集 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "99763916916569088",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://juejin.im/user/3553264960014669/collections",
      "title": "掘金 - 收藏集",
      "type": "feed",
      "url": "rsshub://juejin/collections/3553264960014669"
    },
    {
      "description": "掘金，指定用户整个收藏集 - Powered by RSSHub",
      "errorAt": "2026-01-22T09:33:19.571Z",
      "errorMessage": "Failed to fetch\n",
      "id": "70663680613746688",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://juejin.im/user/430664289093176/collections",
      "title": "掘金 - 收藏集",
      "type": "feed",
      "url": "rsshub://juejin/collections/430664289093176"
    }
  ]
}
```
