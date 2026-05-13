# 雪球 - 股票评论

## Coverage
`index-only`

## Route
- Namespace: `xueqiu`
- Namespace Name: `雪球`
- Route Path: `/stock_comments/:id`
- Route Name: `股票评论`
- Example: `/xueqiu/stock_comments/SZ002626`
- URL: `danjuanapp.com`
- Language: `zh-CN`
- Categories: `finance`
- Maintainers: `None`
- Source Location: `stock-comments.tsx`
- Source Module: `() => import('@/routes/xueqiu/stock-comments.tsx')`

## Description
_None_

## Parameters
- `id`: 股票代码（需要带上交易所）


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
  - `xueqiu.com/S/:id`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/xueqiu/stock_comments/SZ002626",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "stock-comments.tsx",
  "maintainers": [],
  "module": "() => import('@/routes/xueqiu/stock-comments.tsx')",
  "name": "股票评论",
  "parameters": {
    "id": "股票代码（需要带上交易所）"
  },
  "path": "/stock_comments/:id",
  "radar": [
    {
      "source": [
        "xueqiu.com/S/:id"
      ]
    }
  ]
}
```
