# 看漫画 - 漫画更新

## Coverage
`index-only`

## Route
- Namespace: `manhuagui`
- Namespace Name: `看漫画`
- Route Path: `/comic/:id/:chapterCnt?`
- Route Name: `漫画更新`
- Example: `/manhuagui/comic/22942/5`
- URL: `www.manhuagui.com`
- Language: `zh-CN`
- Categories: `anime`
- Maintainers: `MegrezZhu`
- Source Location: `comic.ts`
- Source Module: `() => import('@/routes/manhuagui/comic.ts')`

## Description
_None_

## Parameters
- `id`: 漫画ID
- `chapterCnt`: 返回章节的数量，默认为0，返回所有章节


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `www.mhgui.com/comic/:id/`
- `target`: `/comic/:id`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/manhuagui/comic/22942/5",
  "features": {
    "antiCrawler": true,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "comic.ts",
  "maintainers": [
    "MegrezZhu"
  ],
  "module": "() => import('@/routes/manhuagui/comic.ts')",
  "name": "漫画更新",
  "parameters": {
    "chapterCnt": "返回章节的数量，默认为0，返回所有章节",
    "id": "漫画ID"
  },
  "path": [
    "/comic/:id/:chapterCnt?",
    "/:domain?/comic/:id/:chapterCnt?"
  ],
  "radar": [
    {
      "source": [
        "www.mhgui.com/comic/:id/"
      ],
      "target": "/comic/:id"
    }
  ]
}
```
