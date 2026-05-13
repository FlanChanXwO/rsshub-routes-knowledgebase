# kpopping - News

## Coverage
`index-only`

## Route
- Namespace: `kpopping`
- Namespace Name: `kpopping`
- Route Path: `/news/:filter{.+}?`
- Route Name: `News`
- Example: `/kpopping/news/gender-all/category-all/idol-any/group-any/order`
- URL: `kpopping.com`
- Language: `en`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `news.ts`
- Source Module: `() => import('@/routes/kpopping/news.ts')`

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
  "description": "::: tip\nIf you subscribe to [All male articles](https://kpopping.com/news/gender-male/category-all/idol-any/group-any/order)，where the URL is `https://kpopping.com/news/gender-male/category-all/idol-any/group-any/order`, extract the part `https://kpopping.com/news` to the end, which is `gender-male/category-all/idol-any/group-any/order`, and use it as the parameter to fill in. Therefore, the route will be [`/kpopping/news/gender-male/category-all/idol-any/group-any/order`](https://rsshub.app/kpopping/news/gender-male/category-all/idol-any/group-any/order).\n:::\n",
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
  "location": "news.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/kpopping/news.ts')",
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
  "url": "kpopping.com",
  "view": 0,
  "zh": {
    "description": "::: tip\n若订阅 [All male articles](https://kpopping.com/news/gender-male/category-all/idol-any/group-any/order)，网址为 `https://kpopping.com/news/gender-male/category-all/idol-any/group-any/order`，请截取 `https://kpopping.com/news/` 到末尾的部分 `gender-male/category-all/idol-any/group-any/order` 作为 `filter` 参数填入，此时目标路由为 [`/kpopping/news/gender-male/category-all/idol-any/group-any/order`](https://rsshub.app/kpopping/news/gender-male/category-all/idol-any/group-any/order)。\n:::\n",
    "example": "/kpopping/news/gender-all/category-all/idol-any/group-any/order",
    "maintainers": [
      "nczitzk"
    ],
    "name": "News",
    "parameters": {
      "filter": "筛选，可在对应分类页 URL 中找到"
    },
    "path": "/news/:filter{.+}?",
    "url": "kpopping.com"
  }
}
```
