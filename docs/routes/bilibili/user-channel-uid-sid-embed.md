# 哔哩哔哩 bilibili - UP 主频道的视频列表

## Coverage
`index-only`

## Route
- Namespace: `bilibili`
- Namespace Name: `哔哩哔哩 bilibili`
- Route Path: `/user/channel/:uid/:sid/:embed?`
- Route Name: `UP 主频道的视频列表`
- Example: `/bilibili/user/channel/2267573/396050`
- URL: `www.bilibili.com`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `weirongxu`
- Source Location: `user-channel.ts`
- Source Module: `() => import('@/routes/bilibili/user-channel.ts')`

## Description
_None_

## Parameters
- `uid`: 用户 id, 可在 UP 主主页中找到
- `sid`: 频道 id, 可在频道的 URL 中找到
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
  "example": "/bilibili/user/channel/2267573/396050",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "user-channel.ts",
  "maintainers": [
    "weirongxu"
  ],
  "module": "() => import('@/routes/bilibili/user-channel.ts')",
  "name": "UP 主频道的视频列表",
  "parameters": {
    "embed": "默认为开启内嵌视频, 任意值为关闭",
    "sid": "频道 id, 可在频道的 URL 中找到",
    "uid": "用户 id, 可在 UP 主主页中找到"
  },
  "path": "/user/channel/:uid/:sid/:embed?"
}
```
