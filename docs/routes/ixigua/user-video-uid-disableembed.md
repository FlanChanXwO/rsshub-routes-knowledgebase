# 西瓜视频 - 用户视频投稿

## Coverage
`index-only`

## Route
- Namespace: `ixigua`
- Namespace Name: `西瓜视频`
- Route Path: `/user/video/:uid/:disableEmbed?`
- Route Name: `用户视频投稿`
- Example: `/ixigua/user/video/4234740937`
- URL: `ixigua.com`
- Language: `zh-CN`
- Categories: `multimedia`
- Maintainers: `FlashWingShadow, Fatpandac, pseudoyu`
- Source Location: `user-video.tsx`
- Source Module: `() => import('@/routes/ixigua/user-video.tsx')`

## Description
_None_

## Parameters
- `uid`: 用户 id, 可在用户主页中找到
- `disableEmbed`: 默认为开启内嵌视频, 任意值为关闭


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
  - `ixigua.com/home/:uid`
- `target`: `/user/video/:uid`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/ixigua/user/video/4234740937",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "user-video.tsx",
  "maintainers": [
    "FlashWingShadow",
    "Fatpandac",
    "pseudoyu"
  ],
  "module": "() => import('@/routes/ixigua/user-video.tsx')",
  "name": "用户视频投稿",
  "parameters": {
    "disableEmbed": "默认为开启内嵌视频, 任意值为关闭",
    "uid": "用户 id, 可在用户主页中找到"
  },
  "path": "/user/video/:uid/:disableEmbed?",
  "radar": [
    {
      "source": [
        "ixigua.com/home/:uid"
      ],
      "target": "/user/video/:uid"
    }
  ]
}
```
