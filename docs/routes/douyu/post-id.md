# 斗鱼直播 - 鱼吧跟帖

## Coverage
`index-only`

## Route
- Namespace: `douyu`
- Namespace Name: `斗鱼直播`
- Route Path: `/post/:id`
- Route Name: `鱼吧跟帖`
- Example: `/douyu/post/631737151576473201`
- URL: `www.douyu.com`
- Language: `zh-CN`
- Categories: `bbs`
- Maintainers: `nczitzk`
- Source Location: `post.ts`
- Source Module: `() => import('@/routes/douyu/post.ts')`

## Description
_None_

## Parameters
- `id`: 帖子 id，可在帖子页 URL 中找到


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
  - `yuba.douyu.com/p/:id`
  - `yuba.douyu.com/`

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "example": "/douyu/post/631737151576473201",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "post.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/douyu/post.ts')",
  "name": "鱼吧跟帖",
  "parameters": {
    "id": "帖子 id，可在帖子页 URL 中找到"
  },
  "path": "/post/:id",
  "radar": [
    {
      "source": [
        "yuba.douyu.com/p/:id",
        "yuba.douyu.com/"
      ]
    }
  ]
}
```
