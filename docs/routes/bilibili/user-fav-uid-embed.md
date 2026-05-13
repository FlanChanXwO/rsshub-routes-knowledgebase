# 哔哩哔哩 bilibili - UP 主默认收藏夹

## Coverage
`index-only`

## Route
- Namespace: `bilibili`
- Namespace Name: `哔哩哔哩 bilibili`
- Route Path: `/user/fav/:uid/:embed?`
- Route Name: `UP 主默认收藏夹`
- Example: `/bilibili/user/fav/2267573`
- URL: `www.bilibili.com`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `DIYgod`
- Source Location: `user-fav.ts`
- Source Module: `() => import('@/routes/bilibili/user-fav.ts')`

## Description
_None_

## Parameters
- `uid`: 用户 id, 可在 UP 主主页中找到
- `embed`: 默认为开启内嵌视频, 任意值为关闭


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
  - `space.bilibili.com/:uid`
  - `space.bilibili.com/:uid/favlist`
- `target`: `/user/fav/:uid`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/bilibili/user/fav/2267573",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "user-fav.ts",
  "maintainers": [
    "DIYgod"
  ],
  "module": "() => import('@/routes/bilibili/user-fav.ts')",
  "name": "UP 主默认收藏夹",
  "parameters": {
    "embed": "默认为开启内嵌视频, 任意值为关闭",
    "uid": "用户 id, 可在 UP 主主页中找到"
  },
  "path": "/user/fav/:uid/:embed?",
  "radar": [
    {
      "source": [
        "space.bilibili.com/:uid",
        "space.bilibili.com/:uid/favlist"
      ],
      "target": "/user/fav/:uid"
    }
  ]
}
```
