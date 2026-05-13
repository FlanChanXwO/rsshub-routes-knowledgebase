# 雪球 - 用户收藏动态

## Coverage
`index-only`

## Route
- Namespace: `xueqiu`
- Namespace Name: `雪球`
- Route Path: `/favorite/:id`
- Route Name: `用户收藏动态`
- Example: `/xueqiu/favorite/8152922548`
- URL: `danjuanapp.com`
- Language: `zh-CN`
- Categories: `finance`
- Maintainers: `imlonghao`
- Source Location: `favorite.ts`
- Source Module: `() => import('@/routes/xueqiu/favorite.ts')`

## Description
_None_

## Parameters
- `id`: 用户 id, 可在用户主页 URL 中找到


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
  - `xueqiu.com/u/:id`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/xueqiu/favorite/8152922548",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "favorite.ts",
  "maintainers": [
    "imlonghao"
  ],
  "module": "() => import('@/routes/xueqiu/favorite.ts')",
  "name": "用户收藏动态",
  "parameters": {
    "id": "用户 id, 可在用户主页 URL 中找到"
  },
  "path": "/favorite/:id",
  "radar": [
    {
      "source": [
        "xueqiu.com/u/:id"
      ]
    }
  ]
}
```
