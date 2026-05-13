# 哔哩哔哩 bilibili - link 公告

## Coverage
`index-only`

## Route
- Namespace: `bilibili`
- Namespace Name: `哔哩哔哩 bilibili`
- Route Path: `/link/news/:product`
- Route Name: `link 公告`
- Example: `/bilibili/link/news/live`
- URL: `www.bilibili.com`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `Qixingchen`
- Source Location: `link-news.ts`
- Source Module: `() => import('@/routes/bilibili/link-news.ts')`

## Description
_None_

## Parameters
- `product`: 公告分类, 包括 直播:live 小视频:vc 相簿:wh


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
  "example": "/bilibili/link/news/live",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "link-news.ts",
  "maintainers": [
    "Qixingchen"
  ],
  "module": "() => import('@/routes/bilibili/link-news.ts')",
  "name": "link 公告",
  "parameters": {
    "product": "公告分类, 包括 直播:live 小视频:vc 相簿:wh"
  },
  "path": "/link/news/:product"
}
```
