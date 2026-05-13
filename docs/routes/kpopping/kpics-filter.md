# kpopping - Pics

## Coverage
`index-only`

## Route
- Namespace: `kpopping`
- Namespace Name: `kpopping`
- Route Path: `/kpics/:filter{.+}?`
- Route Name: `Pics`
- Example: `/kpopping/kpics/gender-male/category-all/idol-any/group-any/order`
- URL: `kpopping.com`
- Language: `en`
- Categories: `picture`
- Maintainers: `nczitzk`
- Source Location: `kpics.ts`
- Source Module: `() => import('@/routes/kpopping/kpics.ts')`

## Description
::: tip
If you subscribe to [All male photo albums](https://kpopping.com/kpics/gender-male/category-all/idol-any/group-any/order)，where the URL is `https://kpopping.com/kpics/gender-male/category-all/idol-any/group-any/order`, extract the part `https://kpopping.com/kpics/` to the end, which is `gender-male/category-all/idol-any/group-any/order`, and use it as the parameter to fill in. Therefore, the route will be [`/kpopping/kpics/gender-male/category-all/idol-any/group-any/order`](https://rsshub.app/kpopping/kpics/gender-male/category-all/idol-any/group-any/order).
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
  - `kpopping.com/kpics/:filter`

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "description": "::: tip\nIf you subscribe to [All male photo albums](https://kpopping.com/kpics/gender-male/category-all/idol-any/group-any/order)，where the URL is `https://kpopping.com/kpics/gender-male/category-all/idol-any/group-any/order`, extract the part `https://kpopping.com/kpics/` to the end, which is `gender-male/category-all/idol-any/group-any/order`, and use it as the parameter to fill in. Therefore, the route will be [`/kpopping/kpics/gender-male/category-all/idol-any/group-any/order`](https://rsshub.app/kpopping/kpics/gender-male/category-all/idol-any/group-any/order).\n:::",
  "example": "/kpopping/kpics/gender-male/category-all/idol-any/group-any/order",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "kpics.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/kpopping/kpics.ts')",
  "name": "Pics",
  "parameters": {
    "filter": "Filter"
  },
  "path": "/kpics/:filter{.+}?",
  "radar": [
    {
      "source": [
        "kpopping.com/kpics/:filter"
      ]
    }
  ],
  "url": "kpopping.com",
  "view": 0,
  "zh": {
    "description": "::: tip\n若订阅 [All male photo albums](https://kpopping.com/kpics/gender-male/category-all/idol-any/group-any/order)，网址为 `https://kpopping.com/kpics/gender-male/category-all/idol-any/group-any/order`，请截取 `https://kpopping.com/kpics/` 到末尾的部分 `gender-male/category-all/idol-any/group-any/order` 作为 `filter` 参数填入，此时目标路由为 [`/kpopping/kpics/gender-male/category-all/idol-any/group-any/order`](https://rsshub.app/kpopping/kpics/gender-male/category-all/idol-any/group-any/order)。\n:::\n",
    "example": "/kpopping/kpics/gender-male/category-all/idol-any/group-any/order",
    "maintainers": [
      "nczitzk"
    ],
    "name": "Pics",
    "parameters": {
      "filter": "筛选，可在对应分类页 URL 中找到"
    },
    "path": "/kpics/:filter{.+}?",
    "url": "kpopping.com"
  }
}
```
