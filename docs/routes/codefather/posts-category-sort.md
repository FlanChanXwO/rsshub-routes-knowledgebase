# 编程导航 - 帖子

## Coverage
`index-only`

## Route
- Namespace: `codefather`
- Namespace Name: `编程导航`
- Route Path: `/posts/:category?/:sort?`
- Route Name: `帖子`
- Example: `/codefather/posts`
- URL: `www.codefather.cn`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `JackyST0`
- Source Location: `posts.ts`
- Source Module: `() => import('@/routes/codefather/posts.ts')`

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
  "location": "posts.ts",
  "maintainers": [
    "JackyST0"
  ],
  "module": "() => import('@/routes/codefather/posts.ts')",
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
  ]
}
```
