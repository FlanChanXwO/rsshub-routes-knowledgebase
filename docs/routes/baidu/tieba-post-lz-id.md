# 百度 - 帖子动态

## Coverage
`index-only`

## Route
- Namespace: `baidu`
- Namespace Name: `百度`
- Route Path: `/tieba/post/lz/:id`
- Route Name: `帖子动态`
- Example: `/baidu/tieba/post/686961453`
- URL: `www.baidu.com`
- Language: `zh-CN`
- Categories: `bbs`
- Maintainers: `u3u`
- Source Location: `tieba/post.tsx`
- Source Module: `() => import('@/routes/baidu/tieba/post.tsx')`

## Description
_None_

## Parameters
- `id`: 帖子 ID


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `tieba.baidu.com/p/:id`

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "example": "/baidu/tieba/post/686961453",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "tieba/post.tsx",
  "maintainers": [
    "u3u"
  ],
  "module": "() => import('@/routes/baidu/tieba/post.tsx')",
  "name": "帖子动态",
  "parameters": {
    "id": "帖子 ID"
  },
  "path": [
    "/tieba/post/:id",
    "/tieba/post/lz/:id"
  ],
  "radar": [
    {
      "source": [
        "tieba.baidu.com/p/:id"
      ]
    }
  ]
}
```
