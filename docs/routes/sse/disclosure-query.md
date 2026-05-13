# 上海证券交易所 - 上市公司信息最新公告披露

## Coverage
`index-only`

## Route
- Namespace: `sse`
- Namespace Name: `上海证券交易所`
- Route Path: `/disclosure/:query?`
- Route Name: `上市公司信息最新公告披露`
- Example: `/sse/disclosure/beginDate=2018-08-18&endDate=2020-08-25&productId=600696`
- URL: `bond.sse.com.cn`
- Language: `zh-CN`
- Categories: `finance`
- Maintainers: `harveyqiu`
- Source Location: `disclosure.ts`
- Source Module: `() => import('@/routes/sse/disclosure.ts')`

## Description
_None_

## Parameters
- `query`: 筛选条件，见示例


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
  "example": "/sse/disclosure/beginDate=2018-08-18&endDate=2020-08-25&productId=600696",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "disclosure.ts",
  "maintainers": [
    "harveyqiu"
  ],
  "module": "() => import('@/routes/sse/disclosure.ts')",
  "name": "上市公司信息最新公告披露",
  "parameters": {
    "query": "筛选条件，见示例"
  },
  "path": "/disclosure/:query?"
}
```
