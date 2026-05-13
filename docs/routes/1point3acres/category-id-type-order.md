# 一亩三分地 - 标签

## Coverage
`index-only`

## Route
- Namespace: `1point3acres`
- Namespace Name: `一亩三分地`
- Route Path: `/category/:id?/:type?/:order?`
- Route Name: `标签`
- Example: `/1point3acres/category/h1b`
- URL: `blog.1point3acres.com`
- Language: `zh-CN`
- Categories: `bbs`
- Maintainers: `nczitzk`
- Source Location: `category.ts`
- Source Module: `() => import('@/routes/1point3acres/category.ts')`

## Description
::: tip
  更多标签可以在 [标签列表](https://instant.1point3acres.com/tags) 中找到。
:::

  分类

| 热门帖子 | 最新帖子 |
| -------- | -------- |
| hot      | new      |

  排序方式

| 最新回复 | 最新发布 |
| -------- | -------- |
|          | post     |

## Parameters
- `id`: 标签 id，默认为全部
- `type`: 帖子分类, 见下表，默认为 hot，即热门帖子
- `order`: 排序方式，见下表，默认为空，即最新回复


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
  - `instant.1point3acres.com/section/:id`
  - `instant.1point3acres.com/`

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "description": "::: tip\n  更多标签可以在 [标签列表](https://instant.1point3acres.com/tags) 中找到。\n:::\n\n  分类\n\n| 热门帖子 | 最新帖子 |\n| -------- | -------- |\n| hot      | new      |\n\n  排序方式\n\n| 最新回复 | 最新发布 |\n| -------- | -------- |\n|          | post     |",
  "example": "/1point3acres/category/h1b",
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
    "nczitzk"
  ],
  "module": "() => import('@/routes/1point3acres/category.ts')",
  "name": "标签",
  "parameters": {
    "id": "标签 id，默认为全部",
    "order": "排序方式，见下表，默认为空，即最新回复",
    "type": "帖子分类, 见下表，默认为 hot，即热门帖子"
  },
  "path": "/category/:id?/:type?/:order?",
  "radar": [
    {
      "source": [
        "instant.1point3acres.com/section/:id",
        "instant.1point3acres.com/"
      ]
    }
  ]
}
```
