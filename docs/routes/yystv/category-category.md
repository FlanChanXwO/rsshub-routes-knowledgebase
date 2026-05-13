# 游研社 - 游研社 - 分类文章

## Coverage
`index-only`

## Route
- Namespace: `yystv`
- Namespace Name: `游研社`
- Route Path: `/category/:category`
- Route Name: `游研社 - 分类文章`
- Example: `/yystv/category/recommend`
- URL: `yystv.cn`
- Language: `zh-CN`
- Categories: `game`
- Maintainers: `betta-cyber, dousha`
- Source Location: `category.ts`
- Source Module: `() => import('@/routes/yystv/category.ts')`

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
  "location": "category.ts",
  "maintainers": [
    "betta-cyber",
    "dousha"
  ],
  "module": "() => import('@/routes/yystv/category.ts')",
  "name": "游研社 - 分类文章",
  "parameters": {
    "category": "专栏类型"
  },
  "path": "/category/:category"
}
```
