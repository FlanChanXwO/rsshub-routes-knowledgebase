# 哔哩哔哩 bilibili - 视频选集列表

## Coverage
`index-only`

## Route
- Namespace: `bilibili`
- Namespace Name: `哔哩哔哩 bilibili`
- Route Path: `/video/page/:bvid/:embed?`
- Route Name: `视频选集列表`
- Example: `/bilibili/video/page/BV1i7411M7N9`
- URL: `www.bilibili.com`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `sxzz`
- Source Location: `page.ts`
- Source Module: `() => import('@/routes/bilibili/page.ts')`

## Description
_None_

## Parameters
- `bvid`: 可在视频页 URL 中找到
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
  "example": "/bilibili/video/page/BV1i7411M7N9",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "page.ts",
  "maintainers": [
    "sxzz"
  ],
  "module": "() => import('@/routes/bilibili/page.ts')",
  "name": "视频选集列表",
  "parameters": {
    "bvid": "可在视频页 URL 中找到",
    "embed": "默认为开启内嵌视频, 任意值为关闭"
  },
  "path": "/video/page/:bvid/:embed?"
}
```
