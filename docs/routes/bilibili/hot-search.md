# 哔哩哔哩 bilibili - 热搜

## Coverage
`index-only`

## Route
- Namespace: `bilibili`
- Namespace Name: `哔哩哔哩 bilibili`
- Route Path: `/hot-search`
- Route Name: `热搜`
- Example: `/bilibili/hot-search`
- URL: `www.bilibili.com/`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `CaoMeiYouRen`
- Source Location: `hot-search.ts`
- Source Module: `() => import('@/routes/bilibili/hot-search.ts')`

## Description
_None_

## Parameters
_None_


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
  - `www.bilibili.com/`
### Rule 2
- `source`:
  - `m.bilibili.com/`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/bilibili/hot-search",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "hot-search.ts",
  "maintainers": [
    "CaoMeiYouRen"
  ],
  "module": "() => import('@/routes/bilibili/hot-search.ts')",
  "name": "热搜",
  "parameters": {},
  "path": "/hot-search",
  "radar": [
    {
      "source": [
        "www.bilibili.com/"
      ]
    },
    {
      "source": [
        "m.bilibili.com/"
      ]
    }
  ],
  "url": "www.bilibili.com/"
}
```
