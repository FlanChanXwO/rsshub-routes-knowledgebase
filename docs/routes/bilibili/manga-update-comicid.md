# 哔哩哔哩 bilibili - 漫画更新

## Coverage
`index-only`

## Route
- Namespace: `bilibili`
- Namespace Name: `哔哩哔哩 bilibili`
- Route Path: `/manga/update/:comicid`
- Route Name: `漫画更新`
- Example: `/bilibili/manga/update/26009`
- URL: `www.bilibili.com`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `hoilc`
- Source Location: `manga-update.ts`
- Source Module: `() => import('@/routes/bilibili/manga-update.ts')`

## Description
_None_

## Parameters
- `comicid`: 漫画 id, 可在 URL 中找到, 支持带有`mc`前缀


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
  - `manga.bilibili.com/detail/:comicid`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/bilibili/manga/update/26009",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "manga-update.ts",
  "maintainers": [
    "hoilc"
  ],
  "module": "() => import('@/routes/bilibili/manga-update.ts')",
  "name": "漫画更新",
  "parameters": {
    "comicid": "漫画 id, 可在 URL 中找到, 支持带有`mc`前缀"
  },
  "path": "/manga/update/:comicid",
  "radar": [
    {
      "source": [
        "manga.bilibili.com/detail/:comicid"
      ]
    }
  ]
}
```
