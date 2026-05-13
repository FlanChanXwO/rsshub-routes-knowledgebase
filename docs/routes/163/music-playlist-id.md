# 网易公开课 - 歌单歌曲

## Coverage
`index-only`

## Route
- Namespace: `163`
- Namespace Name: `网易公开课`
- Route Path: `/music/playlist/:id`
- Route Name: `歌单歌曲`
- Example: `/163/music/playlist/35798529`
- URL: `163.com`
- Language: `zh-CN`
- Categories: `multimedia`
- Maintainers: `DIYgod`
- Source Location: `music/playlist.ts`
- Source Module: `() => import('@/routes/163/music/playlist.ts')`

## Description
_None_

## Parameters
- `id`: 歌单 id, 可在歌单页 URL 中找到


## Features
- `requireConfig`: [{"description": "网易云音乐登陆后的 cookie 值，可在浏览器控制台通过`document.cookie`获取。", "name": "NCM_COOKIES", "optional": true}]
- `requirePuppeteer`: false
- `antiCrawler`: true
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
  "example": "/163/music/playlist/35798529",
  "features": {
    "antiCrawler": true,
    "requireConfig": [
      {
        "description": "网易云音乐登陆后的 cookie 值，可在浏览器控制台通过`document.cookie`获取。",
        "name": "NCM_COOKIES",
        "optional": true
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "music/playlist.ts",
  "maintainers": [
    "DIYgod"
  ],
  "module": "() => import('@/routes/163/music/playlist.ts')",
  "name": "歌单歌曲",
  "parameters": {
    "id": "歌单 id, 可在歌单页 URL 中找到"
  },
  "path": "/music/playlist/:id"
}
```
