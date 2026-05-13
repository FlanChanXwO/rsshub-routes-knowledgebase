# 品葱 - 发现

## Coverage
`index-only`

## Route
- Namespace: `pincong`
- Namespace Name: `品葱`
- Route Path: `/category/:category?/:sort?`
- Route Name: `发现`
- Example: `/pincong/category/1/new`
- URL: `pincong.rocks`
- Language: `zh-CN`
- Categories: `bbs`
- Maintainers: `zphw`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/pincong/index.ts')`

## Description
| 最新 | 推荐      | 热门 |
| ---- | --------- | ---- |
| new  | recommend | hot  |

## Parameters
- `category`: 分类，与官网分类 URL `category-` 后的数字对应，默认为全部
- `sort`: 排序方式，参数可见下表，默认为推荐


## Features
- `requireConfig`: false
- `requirePuppeteer`: true
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "description": "| 最新 | 推荐      | 热门 |\n| ---- | --------- | ---- |\n| new  | recommend | hot  |",
  "example": "/pincong/category/1/new",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.ts",
  "maintainers": [
    "zphw"
  ],
  "module": "() => import('@/routes/pincong/index.ts')",
  "name": "发现",
  "parameters": {
    "category": "分类，与官网分类 URL `category-` 后的数字对应，默认为全部",
    "sort": "排序方式，参数可见下表，默认为推荐"
  },
  "path": "/category/:category?/:sort?"
}
```
