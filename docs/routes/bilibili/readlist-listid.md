# 哔哩哔哩 bilibili - 专栏文集

## Coverage
`index-only`

## Route
- Namespace: `bilibili`
- Namespace Name: `哔哩哔哩 bilibili`
- Route Path: `/readlist/:listid`
- Route Name: `专栏文集`
- Example: `/bilibili/readlist/25611`
- URL: `www.bilibili.com`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `hoilc`
- Source Location: `readlist.ts`
- Source Module: `() => import('@/routes/bilibili/readlist.ts')`

## Description
_None_

## Parameters
- `listid`: 文集 id, 可在专栏文集 URL 中找到


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
  "example": "/bilibili/readlist/25611",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "readlist.ts",
  "maintainers": [
    "hoilc"
  ],
  "module": "() => import('@/routes/bilibili/readlist.ts')",
  "name": "专栏文集",
  "parameters": {
    "listid": "文集 id, 可在专栏文集 URL 中找到"
  },
  "path": "/readlist/:listid",
  "view": 0
}
```
