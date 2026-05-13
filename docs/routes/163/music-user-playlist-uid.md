# 网易公开课 - 用户歌单

## Coverage
`index-only`

## Route
- Namespace: `163`
- Namespace Name: `网易公开课`
- Route Path: `/music/user/playlist/:uid`
- Route Name: `用户歌单`
- Example: `/163/music/user/playlist/45441555`
- URL: `163.com`
- Language: `zh-CN`
- Categories: `multimedia`
- Maintainers: `DIYgod`
- Source Location: `music/userplaylist.tsx`
- Source Module: `() => import('@/routes/163/music/userplaylist.tsx')`

## Description
_None_

## Parameters
- `uid`: 用户 uid, 可在用户主页 URL 中找到


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
    "multimedia"
  ],
  "example": "/163/music/user/playlist/45441555",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "music/userplaylist.tsx",
  "maintainers": [
    "DIYgod"
  ],
  "module": "() => import('@/routes/163/music/userplaylist.tsx')",
  "name": "用户歌单",
  "parameters": {
    "uid": "用户 uid, 可在用户主页 URL 中找到"
  },
  "path": "/music/user/playlist/:uid"
}
```
