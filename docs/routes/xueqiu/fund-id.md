# 雪球 - 蛋卷基金净值更新

## Coverage
`index-only`

## Route
- Namespace: `xueqiu`
- Namespace Name: `雪球`
- Route Path: `/fund/:id`
- Route Name: `蛋卷基金净值更新`
- Example: `/xueqiu/fund/040008`
- URL: `danjuanapp.com`
- Language: `zh-CN`
- Categories: `finance`
- Maintainers: `HenryQW, NathanDai`
- Source Location: `fund.ts`
- Source Module: `() => import('@/routes/xueqiu/fund.ts')`

## Description
_None_

## Parameters
- `id`: 基金代码, 可在基金主页 URL 中找到. 此路由的数据为场外基金 (`F`开头)


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
    "finance"
  ],
  "example": "/xueqiu/fund/040008",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "fund.ts",
  "maintainers": [
    "HenryQW",
    "NathanDai"
  ],
  "module": "() => import('@/routes/xueqiu/fund.ts')",
  "name": "蛋卷基金净值更新",
  "parameters": {
    "id": "基金代码, 可在基金主页 URL 中找到. 此路由的数据为场外基金 (`F`开头)"
  },
  "path": "/fund/:id"
}
```
