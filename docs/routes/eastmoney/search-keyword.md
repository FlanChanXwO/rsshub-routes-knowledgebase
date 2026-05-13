# 东方财富 - 搜索

## Coverage
`index-only`

## Route
- Namespace: `eastmoney`
- Namespace Name: `东方财富`
- Route Path: `/search/:keyword`
- Route Name: `搜索`
- Example: `/eastmoney/search/web3`
- URL: `data.eastmoney.com`
- Language: `zh-CN`
- Categories: `finance`
- Maintainers: `drgnchan`
- Source Location: `search/index.ts`
- Source Module: `() => import('@/routes/eastmoney/search/index.ts')`

## Description
_None_

## Parameters
- `keyword`: 关键词，可以设置为自己需要检索的关键词


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
  "example": "/eastmoney/search/web3",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "search/index.ts",
  "maintainers": [
    "drgnchan"
  ],
  "module": "() => import('@/routes/eastmoney/search/index.ts')",
  "name": "搜索",
  "parameters": {
    "keyword": "关键词，可以设置为自己需要检索的关键词"
  },
  "path": "/search/:keyword",
  "view": 0
}
```
