# 哔哩哔哩 bilibili - UP 主点赞视频

## Coverage
`index-only`

## Route
- Namespace: `bilibili`
- Namespace Name: `哔哩哔哩 bilibili`
- Route Path: `/user/like/:uid/:embed?`
- Route Name: `UP 主点赞视频`
- Example: `/bilibili/user/like/208259`
- URL: `www.bilibili.com`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `ygguorun`
- Source Location: `like.ts`
- Source Module: `() => import('@/routes/bilibili/like.ts')`

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
- `target`: `/user/like/:uid`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/bilibili/user/like/208259",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "like.ts",
  "maintainers": [
    "ygguorun"
  ],
  "module": "() => import('@/routes/bilibili/like.ts')",
  "name": "UP 主点赞视频",
  "parameters": {
    "embed": "默认为开启内嵌视频, 任意值为关闭",
    "uid": "用户 id, 可在 UP 主主页中找到"
  },
  "path": "/user/like/:uid/:embed?",
  "radar": [
    {
      "source": [
        "space.bilibili.com/:uid"
      ],
      "target": "/user/like/:uid"
    }
  ]
}
```
