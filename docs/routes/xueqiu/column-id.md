# 雪球 - 用户专栏

## Coverage
`index-only`

## Route
- Namespace: `xueqiu`
- Namespace Name: `雪球`
- Route Path: `/column/:id`
- Route Name: `用户专栏`
- Example: `/xueqiu/column/9962554712`
- URL: `danjuanapp.com`
- Language: `zh-CN`
- Categories: `finance`
- Maintainers: `TonyRL, pseudoyu`
- Source Location: `column.ts`
- Source Module: `() => import('@/routes/xueqiu/column.ts')`

## Description
_None_

## Parameters
- `id`: 用户 id, 可在用户主页 URL 中找到


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `xueqiu.com/:id/column`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/xueqiu/column/9962554712",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "column.ts",
  "maintainers": [
    "TonyRL",
    "pseudoyu"
  ],
  "module": "() => import('@/routes/xueqiu/column.ts')",
  "name": "用户专栏",
  "parameters": {
    "id": "用户 id, 可在用户主页 URL 中找到"
  },
  "path": "/column/:id",
  "radar": [
    {
      "source": [
        "xueqiu.com/:id/column"
      ]
    }
  ]
}
```
