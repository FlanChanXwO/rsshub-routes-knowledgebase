# 東立出版社 - 新聞

## Coverage
`index-only`

## Route
- Namespace: `tongli`
- Namespace Name: `東立出版社`
- Route Path: `/news/:type`
- Route Name: `新聞`
- Example: `/tongli/news/6`
- URL: `tongli.com.tw`
- Language: `zh-TW`
- Categories: `reading`
- Maintainers: `CokeMine`
- Source Location: `news.ts`
- Source Module: `() => import('@/routes/tongli/news.ts')`

## Description
_None_

## Parameters
- `type`: 分類，可以在“新聞”鏈接中找到


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
    "reading"
  ],
  "example": "/tongli/news/6",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "news.ts",
  "maintainers": [
    "CokeMine"
  ],
  "module": "() => import('@/routes/tongli/news.ts')",
  "name": "新聞",
  "parameters": {
    "type": "分類，可以在“新聞”鏈接中找到"
  },
  "path": "/news/:type"
}
```
