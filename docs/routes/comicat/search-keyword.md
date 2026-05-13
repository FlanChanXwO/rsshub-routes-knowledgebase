# Comicat - 搜索关键词

## Coverage
`index-only`

## Route
- Namespace: `comicat`
- Namespace Name: `Comicat`
- Route Path: `/search/:keyword`
- Route Name: `搜索关键词`
- Example: `/comicat/search/喵萌奶茶屋+跃动青春+720P+简日`
- URL: `comicat.org`
- Language: `zh-CN`
- Categories: `anime`
- Maintainers: `Cyang39`
- Source Location: `search.ts`
- Source Module: `() => import('@/routes/comicat/search.ts')`

## Description
_None_

## Parameters
- `keyword`: 关键词，请用`+`号连接


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: true
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/comicat/search/喵萌奶茶屋+跃动青春+720P+简日",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": true,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "search.ts",
  "maintainers": [
    "Cyang39"
  ],
  "module": "() => import('@/routes/comicat/search.ts')",
  "name": "搜索关键词",
  "parameters": {
    "keyword": "关键词，请用`+`号连接"
  },
  "path": "/search/:keyword"
}
```
