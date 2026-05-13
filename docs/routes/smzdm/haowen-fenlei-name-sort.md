# 什么值得买 - 好文分类

## Coverage
`index-only`

## Route
- Namespace: `smzdm`
- Namespace Name: `什么值得买`
- Route Path: `/haowen/fenlei/:name/:sort?`
- Route Name: `好文分类`
- Example: `/smzdm/haowen/fenlei/shenghuodianqi`
- URL: `post.smzdm.com`
- Language: `zh-CN`
- Categories: `shopping`
- Maintainers: `LogicJake`
- Source Location: `haowen-fenlei.ts`
- Source Module: `() => import('@/routes/smzdm/haowen-fenlei.ts')`

## Description
| 最新 | 周排行 | 月排行 |
| ---- | ------ | ------ |
| 0    | 7      | 30     |

## Parameters
- `name`: 分类名，可在 URL 中查看
- `sort`: 排序方式，默认为最新


## Features
- `requireConfig`: [{"description": "什么值得买登录后的 Cookie 值", "name": "SMZDM_COOKIE"}]
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `post.smzdm.com/fenlei/:name`
- `target`: `/haowen/fenlei/:name`

## Raw JSON
```json
{
  "categories": [
    "shopping"
  ],
  "description": "| 最新 | 周排行 | 月排行 |\n| ---- | ------ | ------ |\n| 0    | 7      | 30     |",
  "example": "/smzdm/haowen/fenlei/shenghuodianqi",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "什么值得买登录后的 Cookie 值",
        "name": "SMZDM_COOKIE"
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "haowen-fenlei.ts",
  "maintainers": [
    "LogicJake"
  ],
  "module": "() => import('@/routes/smzdm/haowen-fenlei.ts')",
  "name": "好文分类",
  "parameters": {
    "name": "分类名，可在 URL 中查看",
    "sort": "排序方式，默认为最新"
  },
  "path": "/haowen/fenlei/:name/:sort?",
  "radar": [
    {
      "source": [
        "post.smzdm.com/fenlei/:name"
      ],
      "target": "/haowen/fenlei/:name"
    }
  ]
}
```
