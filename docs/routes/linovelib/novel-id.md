# 哔哩轻小说 - 小说更新

## Coverage
`index-only`

## Route
- Namespace: `linovelib`
- Namespace Name: `哔哩轻小说`
- Route Path: `/novel/:id`
- Route Name: `小说更新`
- Example: `/linovelib/novel/2547`
- URL: `linovelib.com`
- Language: `zh-CN`
- Categories: `reading`
- Maintainers: `misakicoca`
- Source Location: `novel.ts`
- Source Module: `() => import('@/routes/linovelib/novel.ts')`

## Description
_None_

## Parameters
- `id`: 小说 id，对应书架开始阅读 URL 中找到


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "reading"
  ],
  "example": "/linovelib/novel/2547",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "novel.ts",
  "maintainers": [
    "misakicoca"
  ],
  "module": "() => import('@/routes/linovelib/novel.ts')",
  "name": "小说更新",
  "parameters": {
    "id": "小说 id，对应书架开始阅读 URL 中找到"
  },
  "path": "/novel/:id"
}
```
