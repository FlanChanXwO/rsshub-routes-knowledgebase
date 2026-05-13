# 哔哩哔哩 bilibili - B 站每周必看

## Coverage
`index-only`

## Route
- Namespace: `bilibili`
- Namespace Name: `哔哩哔哩 bilibili`
- Route Path: `/weekly/:embed?`
- Route Name: `B 站每周必看`
- Example: `/bilibili/weekly`
- URL: `www.bilibili.com`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `ttttmr`
- Source Location: `weekly-recommend.ts`
- Source Module: `() => import('@/routes/bilibili/weekly-recommend.ts')`

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
  "example": "/bilibili/weekly",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "weekly-recommend.ts",
  "maintainers": [
    "ttttmr"
  ],
  "module": "() => import('@/routes/bilibili/weekly-recommend.ts')",
  "name": "B 站每周必看",
  "parameters": {
    "embed": "默认为开启内嵌视频, 任意值为关闭"
  },
  "path": "/weekly/:embed?"
}
```
