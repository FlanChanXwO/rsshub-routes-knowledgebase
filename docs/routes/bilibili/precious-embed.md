# 哔哩哔哩 bilibili - 入站必刷

## Coverage
`index-only`

## Route
- Namespace: `bilibili`
- Namespace Name: `哔哩哔哩 bilibili`
- Route Path: `/precious/:embed?`
- Route Name: `入站必刷`
- Example: `/bilibili/precious`
- URL: `www.bilibili.com`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `liuyuhe666`
- Source Location: `bilibili-recommend.ts`
- Source Module: `() => import('@/routes/bilibili/bilibili-recommend.ts')`

## Description
_None_

## Parameters
- `embed`: 默认为开启内嵌视频, 任意值为关闭


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
    "social-media"
  ],
  "example": "/bilibili/precious",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "bilibili-recommend.ts",
  "maintainers": [
    "liuyuhe666"
  ],
  "module": "() => import('@/routes/bilibili/bilibili-recommend.ts')",
  "name": "入站必刷",
  "parameters": {
    "embed": "默认为开启内嵌视频, 任意值为关闭"
  },
  "path": "/precious/:embed?"
}
```
