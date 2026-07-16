# 编程导航 - 帖子

## Coverage
`index-only`

## Route
- Namespace: `codefather`
- Namespace Name: `编程导航`
- Route Path: `/codefather/posts/:category?/:sort?`
- Route Name: `帖子`
- Example: `/codefather/posts`
- URL: `www.codefather.cn`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `JackyST0`
- Source Location: `posts.ts`
- Source Module: `_None_`

## Description
获取编程导航社区的帖子，支持按热门、最新、推荐排序，支持按分类筛选。

## Parameters
- `category`: 分类，可选 `交流`、`学习`、`项目`、`资源`、`经验`，默认为全部
- `sort`: 排序方式，可选 `new`（最新）、`hot`（热门）、`recommend`（推荐），默认为 `new`


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
  - `www.codefather.cn/`
  - `www.codefather.cn`
- `target`: `/posts`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "description": "获取编程导航社区的帖子，支持按热门、最新、推荐排序，支持按分类筛选。",
  "example": "/codefather/posts",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 3,
  "location": "posts.ts",
  "maintainers": [
    "JackyST0"
  ],
  "name": "帖子",
  "parameters": {
    "category": "分类，可选 `交流`、`学习`、`项目`、`资源`、`经验`，默认为全部",
    "sort": "排序方式，可选 `new`（最新）、`hot`（热门）、`recommend`（推荐），默认为 `new`"
  },
  "path": "/posts/:category?/:sort?",
  "radar": [
    {
      "source": [
        "www.codefather.cn/",
        "www.codefather.cn"
      ],
      "target": "/posts"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "编程导航社区最新帖子 - Powered by RSSHub",
      "errorAt": "2026-07-15T04:38:13.540Z",
      "errorMessage": "Failed to fetch\n",
      "id": "238290887490977792",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.codefather.cn/",
      "title": "编程导航 - 最新帖子",
      "type": "feed",
      "url": "rsshub://codefather/posts"
    }
  ]
}
```
