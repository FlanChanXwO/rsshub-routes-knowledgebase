# 0818 团 - 分类

## Coverage
`index-only`

## Route
- Namespace: `0818tuan`
- Namespace Name: `0818 团`
- Route Path: `/:listId?`
- Route Name: `分类`
- Example: `/0818tuan`
- URL: `0818tuan.com`
- Language: `zh-CN`
- Categories: `shopping`
- Maintainers: `TonyRL`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/0818tuan/index.ts')`

## Description
| 最新线报 | 实测活动 | 优惠券 |
| -------- | -------- | ------ |
| 1        | 2        | 3      |

## Parameters
- `listId`: 活动分类，见下表，默认为 `1`


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
    "shopping"
  ],
  "description": "| 最新线报 | 实测活动 | 优惠券 |\n| -------- | -------- | ------ |\n| 1        | 2        | 3      |",
  "example": "/0818tuan",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/0818tuan/index.ts')",
  "name": "分类",
  "parameters": {
    "listId": "活动分类，见下表，默认为 `1`"
  },
  "path": "/:listId?"
}
```
