# 掘金 - 小册

## Coverage
`index-only`

## Route
- Namespace: `juejin`
- Namespace Name: `掘金`
- Route Path: `/books`
- Route Name: `小册`
- Example: `/juejin/books`
- URL: `juejin.cn/books`
- Language: `zh-CN`
- Categories: `programming`
- Maintainers: `xyqfer`
- Source Location: `books.ts`
- Source Module: `() => import('@/routes/juejin/books.ts')`

## Description
> 掘金小册需要付费订阅，RSS 仅做更新提醒，不含付费内容.

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
  - `juejin.cn/books`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "description": "> 掘金小册需要付费订阅，RSS 仅做更新提醒，不含付费内容.",
  "example": "/juejin/books",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "books.ts",
  "maintainers": [
    "xyqfer"
  ],
  "module": "() => import('@/routes/juejin/books.ts')",
  "name": "小册",
  "parameters": {},
  "path": "/books",
  "radar": [
    {
      "source": [
        "juejin.cn/books"
      ]
    }
  ],
  "url": "juejin.cn/books"
}
```
