# 逛丢 - 九块九

## Coverage
`index-only`

## Route
- Namespace: `guangdiu`
- Namespace Name: `逛丢`
- Route Path: `/cheaps/:query?`
- Route Name: `九块九`
- Example: `/guangdiu/cheaps/k=clothes`
- URL: `guangdiu.com`
- Language: `zh-CN`
- Categories: `shopping`
- Maintainers: `fatpandac`
- Source Location: `cheaps.ts`
- Source Module: `() => import('@/routes/guangdiu/cheaps.ts')`

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
  "example": "/guangdiu/cheaps/k=clothes",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "cheaps.ts",
  "maintainers": [
    "fatpandac"
  ],
  "module": "() => import('@/routes/guangdiu/cheaps.ts')",
  "name": "九块九",
  "parameters": {
    "query": "链接参数，对应网址问号后的内容"
  },
  "path": "/cheaps/:query?"
}
```
