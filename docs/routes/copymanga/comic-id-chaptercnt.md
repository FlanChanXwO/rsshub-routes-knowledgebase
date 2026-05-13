# 拷贝漫画 - 漫画更新

## Coverage
`index-only`

## Route
- Namespace: `copymanga`
- Namespace Name: `拷贝漫画`
- Route Path: `/comic/:id/:chapterCnt?`
- Route Name: `漫画更新`
- Example: `/copymanga/comic/dianjuren/5`
- URL: `copymanga.com`
- Language: `zh-CN`
- Categories: `anime`
- Maintainers: `btdwv, marvolo666`
- Source Location: `comic.tsx`
- Source Module: `() => import('@/routes/copymanga/comic.tsx')`

## Description
_None_

## Parameters
- `id`: 漫画ID
- `chapterCnt`: 返回章节的数量，默认为 `10`


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/copymanga/comic/dianjuren/5",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "comic.tsx",
  "maintainers": [
    "btdwv",
    "marvolo666"
  ],
  "module": "() => import('@/routes/copymanga/comic.tsx')",
  "name": "漫画更新",
  "parameters": {
    "chapterCnt": "返回章节的数量，默认为 `10`",
    "id": "漫画ID"
  },
  "path": "/comic/:id/:chapterCnt?"
}
```
