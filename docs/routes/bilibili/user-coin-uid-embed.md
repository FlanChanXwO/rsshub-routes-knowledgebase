# 哔哩哔哩 bilibili - UP 主投币视频

## Coverage
`index-only`

## Route
- Namespace: `bilibili`
- Namespace Name: `哔哩哔哩 bilibili`
- Route Path: `/user/coin/:uid/:embed?`
- Route Name: `UP 主投币视频`
- Example: `/bilibili/user/coin/208259`
- URL: `www.bilibili.com`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `DIYgod`
- Source Location: `coin.ts`
- Source Module: `() => import('@/routes/bilibili/coin.ts')`

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
- `target`: `/user/coin/:uid`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/bilibili/user/coin/208259",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "coin.ts",
  "maintainers": [
    "DIYgod"
  ],
  "module": "() => import('@/routes/bilibili/coin.ts')",
  "name": "UP 主投币视频",
  "parameters": {
    "embed": "默认为开启内嵌视频, 任意值为关闭",
    "uid": "用户 id, 可在 UP 主主页中找到"
  },
  "path": "/user/coin/:uid/:embed?",
  "radar": [
    {
      "source": [
        "space.bilibili.com/:uid"
      ],
      "target": "/user/coin/:uid"
    }
  ]
}
```
