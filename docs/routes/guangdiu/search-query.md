# 逛丢 - 关键字搜索

## Coverage
`index-only`

## Route
- Namespace: `guangdiu`
- Namespace Name: `逛丢`
- Route Path: `/search/:query?`
- Route Name: `关键字搜索`
- Example: `/guangdiu/search/q=百度网盘`
- URL: `guangdiu.com`
- Language: `zh-CN`
- Categories: `shopping`
- Maintainers: `Huzhixin00`
- Source Location: `search.ts`
- Source Module: `() => import('@/routes/guangdiu/search.ts')`

## Description
_None_

## Parameters
- `query`: 链接参数，对应网址问号后的内容


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
    "shopping"
  ],
  "example": "/guangdiu/search/q=百度网盘",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "search.ts",
  "maintainers": [
    "Huzhixin00"
  ],
  "module": "() => import('@/routes/guangdiu/search.ts')",
  "name": "关键字搜索",
  "parameters": {
    "query": "链接参数，对应网址问号后的内容"
  },
  "path": "/search/:query?"
}
```
