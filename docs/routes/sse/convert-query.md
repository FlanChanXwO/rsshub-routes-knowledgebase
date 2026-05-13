# 上海证券交易所 - 可转换公司债券公告

## Coverage
`index-only`

## Route
- Namespace: `sse`
- Namespace Name: `上海证券交易所`
- Route Path: `/convert/:query?`
- Route Name: `可转换公司债券公告`
- Example: `/sse/convert/beginDate=2018-08-18&endDate=2019-08-18&companyCode=603283&title=股份`
- URL: `bond.sse.com.cn`
- Language: `zh-CN`
- Categories: `finance`
- Maintainers: `kt286`
- Source Location: `convert.ts`
- Source Module: `() => import('@/routes/sse/convert.ts')`

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
  "example": "/sse/convert/beginDate=2018-08-18&endDate=2019-08-18&companyCode=603283&title=股份",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "convert.ts",
  "maintainers": [
    "kt286"
  ],
  "module": "() => import('@/routes/sse/convert.ts')",
  "name": "可转换公司债券公告",
  "parameters": {
    "query": "筛选条件，见示例"
  },
  "path": "/convert/:query?"
}
```
