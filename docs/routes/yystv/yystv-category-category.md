# 游研社 - 游研社 - 分类文章

## Coverage
`index-only`

## Route
- Namespace: `yystv`
- Namespace Name: `游研社`
- Route Path: `/yystv/category/:category`
- Route Name: `游研社 - 分类文章`
- Example: `/yystv/category/recommend`
- URL: `yystv.cn`
- Language: `_None_`
- Categories: `game`
- Maintainers: `betta-cyber, dousha`
- Source Location: `category.ts`
- Source Module: `_None_`

## Description
| 推游      | 游戏史  | 大事件 | 文化    | 趣闻 | 经典回顾 | 业界     |
| --------- | ------- | ------ | ------- | ---- | -------- | -------- |
| recommend | history | big    | culture | news | retro    | industry |

## Parameters
- `category`: 专栏类型


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
    "game"
  ],
  "description": "| 推游      | 游戏史  | 大事件 | 文化    | 趣闻 | 经典回顾 | 业界     |\n| --------- | ------- | ------ | ------- | ---- | -------- | -------- |\n| recommend | history | big    | culture | news | retro    | industry |",
  "example": "/yystv/category/recommend",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 39,
  "location": "category.ts",
  "maintainers": [
    "betta-cyber",
    "dousha"
  ],
  "name": "游研社 - 分类文章",
  "parameters": {
    "category": "专栏类型"
  },
  "path": "/category/:category",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "游研社-推游 - Powered by RSSHub",
      "errorAt": "2025-08-26T12:35:22.570Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "52353637010143243",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.yystv.cn/b/recommend",
      "title": "游研社-推游",
      "type": "feed",
      "url": "rsshub://yystv/category/recommend"
    },
    {
      "description": "游研社-趣闻 - Powered by RSSHub",
      "errorAt": "2025-08-26T16:08:18.138Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "60263446472040463",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.yystv.cn/b/news",
      "title": "游研社-趣闻",
      "type": "feed",
      "url": "rsshub://yystv/category/news"
    }
  ]
}
```
