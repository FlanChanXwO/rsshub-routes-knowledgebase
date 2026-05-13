# kpopping - News

## Coverage
`index-only`

## Route
- Namespace: `kpopping`
- Namespace Name: `kpopping`
- Route Path: `/kpopping/news/:filter{.+}?`
- Route Name: `News`
- Example: `/kpopping/news/gender-all/category-all/idol-any/group-any/order`
- URL: `kpopping.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
::: tip
If you subscribe to [All male articles](https://kpopping.com/news/gender-male/category-all/idol-any/group-any/order)，where the URL is `https://kpopping.com/news/gender-male/category-all/idol-any/group-any/order`, extract the part `https://kpopping.com/news` to the end, which is `gender-male/category-all/idol-any/group-any/order`, and use it as the parameter to fill in. Therefore, the route will be [`/kpopping/news/gender-male/category-all/idol-any/group-any/order`](https://rsshub.app/kpopping/news/gender-male/category-all/idol-any/group-any/order).
:::

## Parameters
- `filter`: Filter


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `kpopping.com/news/:filter`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "::: tip\nIf you subscribe to [All male articles](https://kpopping.com/news/gender-male/category-all/idol-any/group-any/order)，where the URL is `https://kpopping.com/news/gender-male/category-all/idol-any/group-any/order`, extract the part `https://kpopping.com/news` to the end, which is `gender-male/category-all/idol-any/group-any/order`, and use it as the parameter to fill in. Therefore, the route will be [`/kpopping/news/gender-male/category-all/idol-any/group-any/order`](https://rsshub.app/kpopping/news/gender-male/category-all/idol-any/group-any/order).\n:::",
  "example": "/kpopping/news/gender-all/category-all/idol-any/group-any/order",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 0,
  "location": "news.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "News",
  "parameters": {
    "filter": "Filter"
  },
  "path": "/news/:filter{.+}?",
  "radar": [
    {
      "source": [
        "kpopping.com/news/:filter"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "kpopping.com",
  "view": 0,
  "zh": {
    "description": "::: tip\n若订阅 [All male articles](https://kpopping.com/news/gender-male/category-all/idol-any/group-any/order)，网址为 `https://kpopping.com/news/gender-male/category-all/idol-any/group-any/order`，请截取 `https://kpopping.com/news/` 到末尾的部分 `gender-male/category-all/idol-any/group-any/order` 作为 `filter` 参数填入，此时目标路由为 [`/kpopping/news/gender-male/category-all/idol-any/group-any/order`](https://rsshub.app/kpopping/news/gender-male/category-all/idol-any/group-any/order)。\n:::",
    "name": "News",
    "parameters": {
      "filter": "筛选，可在对应分类页 URL 中找到"
    }
  }
}
```
