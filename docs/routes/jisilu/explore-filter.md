# 集思录 - 广场

## Coverage
`index-only`

## Route
- Namespace: `jisilu`
- Namespace Name: `集思录`
- Route Path: `/explore/:filter?`
- Route Name: `广场`
- Example: `/jisilu/explore`
- URL: `www.jisilu.cn`
- Language: `zh-CN`
- Categories: `finance`
- Maintainers: `nczitzk`
- Source Location: `explore.ts`
- Source Module: `() => import('@/routes/jisilu/explore.ts')`

## Description
::: tip
若订阅 [债券/可转债 - 热门 - 30天](https://www.jisilu.cn/home/explore/category-4__sort_type-hot__day-30)，网址为 `https://www.jisilu.cn/home/explore/category-4__sort_type-hot__day-30`，请截取 `https://www.jisilu.cn/home/explore/` 到末尾的部分 `category-4__sort_type-hot__day-30` 作为 `filter` 参数填入，此时目标路由为 [`/jisilu/explore/category-4__sort_type-hot__day-30`](https://rsshub.app/jisilu/explore/category-4__sort_type-hot__day-30)。
:::

## Parameters
- `category`: 过滤器，默认为空，可在对应页 URL 中找到


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
  - `www.jisilu.cn/home/explore/:filter`
  - `www.jisilu.cn/home/explore`
  - `www.jisilu.cn/explore`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "::: tip\n若订阅 [债券/可转债 - 热门 - 30天](https://www.jisilu.cn/home/explore/category-4__sort_type-hot__day-30)，网址为 `https://www.jisilu.cn/home/explore/category-4__sort_type-hot__day-30`，请截取 `https://www.jisilu.cn/home/explore/` 到末尾的部分 `category-4__sort_type-hot__day-30` 作为 `filter` 参数填入，此时目标路由为 [`/jisilu/explore/category-4__sort_type-hot__day-30`](https://rsshub.app/jisilu/explore/category-4__sort_type-hot__day-30)。\n:::\n    ",
  "example": "/jisilu/explore",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "explore.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/jisilu/explore.ts')",
  "name": "广场",
  "parameters": {
    "category": "过滤器，默认为空，可在对应页 URL 中找到"
  },
  "path": "/explore/:filter?",
  "radar": [
    {
      "source": [
        "www.jisilu.cn/home/explore/:filter",
        "www.jisilu.cn/home/explore",
        "www.jisilu.cn/explore"
      ]
    }
  ],
  "url": "www.jisilu.cn",
  "view": 0
}
```
