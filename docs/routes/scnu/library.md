# 华南师范大学 - 图书馆通知

## Coverage
`index-only`

## Route
- Namespace: `scnu`
- Namespace Name: `华南师范大学`
- Route Path: `/library`
- Route Name: `图书馆通知`
- Example: `/scnu/library`
- URL: `lib.scnu.edu.cn/news/zuixingonggao`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `fengkx`
- Source Location: `library.ts`
- Source Module: `() => import('@/routes/scnu/library.ts')`

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
  - `lib.scnu.edu.cn/news/zuixingonggao`
  - `lib.scnu.edu.cn/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/scnu/library",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "library.ts",
  "maintainers": [
    "fengkx"
  ],
  "module": "() => import('@/routes/scnu/library.ts')",
  "name": "图书馆通知",
  "parameters": {},
  "path": "/library",
  "radar": [
    {
      "source": [
        "lib.scnu.edu.cn/news/zuixingonggao",
        "lib.scnu.edu.cn/"
      ]
    }
  ],
  "url": "lib.scnu.edu.cn/news/zuixingonggao"
}
```
