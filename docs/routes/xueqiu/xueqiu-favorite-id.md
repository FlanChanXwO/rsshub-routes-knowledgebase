# 雪球 - 用户收藏动态

## Coverage
`index-only`

## Route
- Namespace: `xueqiu`
- Namespace Name: `雪球`
- Route Path: `/xueqiu/favorite/:id`
- Route Name: `用户收藏动态`
- Example: `/xueqiu/favorite/8152922548`
- URL: `danjuanapp.com`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `imlonghao`
- Source Location: `favorite.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 用户 id, 可在用户主页 URL 中找到


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
  - `xueqiu.com/u/:id`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/xueqiu/favorite/8152922548",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 62,
  "location": "favorite.ts",
  "maintainers": [
    "imlonghao"
  ],
  "name": "用户收藏动态",
  "parameters": {
    "id": "用户 id, 可在用户主页 URL 中找到"
  },
  "path": "/favorite/:id",
  "radar": [
    {
      "source": [
        "xueqiu.com/u/:id"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "大道无形我有型 的雪球收藏动态 - Powered by RSSHub",
      "errorAt": "2025-12-24T04:59:11.751Z",
      "errorMessage": "Cannot read properties of undefined (reading 'screen_name')\n",
      "id": "59965365270185984",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://xueqiu.com/u/1247347556",
      "title": "大道无形我有型 的雪球收藏动态",
      "type": "feed",
      "url": "rsshub://xueqiu/favorite/1247347556"
    },
    {
      "description": "陈达美股投资 的雪球收藏动态 - Powered by RSSHub",
      "errorAt": "2024-12-03T09:58:41.916Z",
      "errorMessage": "Cannot read properties of undefined (reading 'screen_name')\n",
      "id": "86391133411299328",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://xueqiu.com/u/9598793634",
      "title": "陈达美股投资 的雪球收藏动态",
      "type": "feed",
      "url": "rsshub://xueqiu/favorite/9598793634"
    }
  ]
}
```
