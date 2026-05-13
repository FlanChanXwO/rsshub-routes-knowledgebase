# 抖店开放平台 - 平台公告

## Coverage
`index-only`

## Route
- Namespace: `jinritemai`
- Namespace Name: `抖店开放平台`
- Route Path: `/docs/:dirId?`
- Route Name: `平台公告`
- Example: `/jinritemai/docs/19`
- URL: `op.jinritemai.com`
- Language: `zh-CN`
- Categories: `programming`
- Maintainers: `blade0910`
- Source Location: `docs.ts`
- Source Module: `() => import('@/routes/jinritemai/docs.ts')`

## Description
| 类型    | type    |
| --------- | ---------- |
| 全部公告    | 5    |
| 产品发布    | 19   |
| 规则变更    | 21   |
| 维护公告    | 20   |
| 其他公告    | 22   |

## Parameters
- `dirId`: 公告分类, 可在页面URL获取 默认为全部


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
    "programming"
  ],
  "description": "| 类型    | type    |\n| --------- | ---------- |\n| 全部公告    | 5    |\n| 产品发布    | 19   |\n| 规则变更    | 21   |\n| 维护公告    | 20   |\n| 其他公告    | 22   |",
  "example": "/jinritemai/docs/19",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "docs.ts",
  "maintainers": [
    "blade0910"
  ],
  "module": "() => import('@/routes/jinritemai/docs.ts')",
  "name": "平台公告",
  "parameters": {
    "dirId": "公告分类, 可在页面URL获取 默认为全部"
  },
  "path": "/docs/:dirId?"
}
```
