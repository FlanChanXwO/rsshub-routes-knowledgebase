# 澎湃新闻 - 政务号

## Coverage
`index-only`

## Route
- Namespace: `thepaper`
- Namespace Name: `澎湃新闻`
- Route Path: `/gov/:pphId`
- Route Name: `政务号`
- Example: `/thepaper/gov/63850`
- URL: `thepaper.cn`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `occam-7`
- Source Location: `gov.ts`
- Source Module: `() => import('@/routes/thepaper/gov.ts')`

## Description
_None_

## Parameters
- `pphId`: 政务号 id，可在政务号页 URL 中找到


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
    "new-media"
  ],
  "example": "/thepaper/gov/63850",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "gov.ts",
  "maintainers": [
    "occam-7"
  ],
  "module": "() => import('@/routes/thepaper/gov.ts')",
  "name": "政务号",
  "parameters": {
    "pphId": "政务号 id，可在政务号页 URL 中找到"
  },
  "path": "/gov/:pphId"
}
```
