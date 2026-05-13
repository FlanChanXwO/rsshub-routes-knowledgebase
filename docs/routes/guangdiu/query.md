# 逛丢 - 国内折扣 / 海外折扣

## Coverage
`index-only`

## Route
- Namespace: `guangdiu`
- Namespace Name: `逛丢`
- Route Path: `/:query?`
- Route Name: `国内折扣 / 海外折扣`
- Example: `/guangdiu/k=daily`
- URL: `guangdiu.com`
- Language: `zh-CN`
- Categories: `shopping`
- Maintainers: `Fatpandac`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/guangdiu/index.ts')`

## Description
::: tip
  海外折扣: [`/guangdiu/k=daily&c=us`](https://rsshub.app/guangdiu/k=daily&c=us)
:::

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
  "description": "::: tip\n  海外折扣: [`/guangdiu/k=daily&c=us`](https://rsshub.app/guangdiu/k=daily&c=us)\n:::",
  "example": "/guangdiu/k=daily",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.ts",
  "maintainers": [
    "Fatpandac"
  ],
  "module": "() => import('@/routes/guangdiu/index.ts')",
  "name": "国内折扣 / 海外折扣",
  "parameters": {
    "query": "链接参数，对应网址问号后的内容"
  },
  "path": "/:query?"
}
```
