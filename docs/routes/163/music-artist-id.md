# 网易公开课 - 歌手专辑

## Coverage
`index-only`

## Route
- Namespace: `163`
- Namespace Name: `网易公开课`
- Route Path: `/music/artist/:id`
- Route Name: `歌手专辑`
- Example: `/163/music/artist/2116`
- URL: `163.com`
- Language: `zh-CN`
- Categories: `multimedia`
- Maintainers: `metowolf`
- Source Location: `music/artist.ts`
- Source Module: `() => import('@/routes/163/music/artist.ts')`

## Description
_None_

## Parameters
- `id`: 歌手 id, 可在歌手详情页 URL 中找到


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
  "example": "/163/music/artist/2116",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "music/artist.ts",
  "maintainers": [
    "metowolf"
  ],
  "module": "() => import('@/routes/163/music/artist.ts')",
  "name": "歌手专辑",
  "parameters": {
    "id": "歌手 id, 可在歌手详情页 URL 中找到"
  },
  "path": "/music/artist/:id"
}
```
