# 哔哩哔哩 bilibili - UP 主频道的合集

## Coverage
`index-only`

## Route
- Namespace: `bilibili`
- Namespace Name: `哔哩哔哩 bilibili`
- Route Path: `/user/collection/:uid/:sid/:embed?/:sortReverse?/:page?`
- Route Name: `UP 主频道的合集`
- Example: `/bilibili/user/collection/245645656/529166`
- URL: `www.bilibili.com`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `shininome, cscnk52`
- Source Location: `user-collection.ts`
- Source Module: `() => import('@/routes/bilibili/user-collection.ts')`

## Description
_None_

## Parameters
- `uid`: 用户 id, 可在 UP 主主页中找到
- `sid`: 合集 id, 可在合集页面的 URL 中找到
- `embed`: 默认为开启内嵌视频, 任意值为关闭
- `sortReverse`: 默认:默认排序 1:升序排序
- `page`: 页码, 默认1


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
  "example": "/bilibili/user/collection/245645656/529166",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "user-collection.ts",
  "maintainers": [
    "shininome",
    "cscnk52"
  ],
  "module": "() => import('@/routes/bilibili/user-collection.ts')",
  "name": "UP 主频道的合集",
  "parameters": {
    "embed": "默认为开启内嵌视频, 任意值为关闭",
    "page": "页码, 默认1",
    "sid": "合集 id, 可在合集页面的 URL 中找到",
    "sortReverse": "默认:默认排序 1:升序排序",
    "uid": "用户 id, 可在 UP 主主页中找到"
  },
  "path": "/user/collection/:uid/:sid/:embed?/:sortReverse?/:page?"
}
```
