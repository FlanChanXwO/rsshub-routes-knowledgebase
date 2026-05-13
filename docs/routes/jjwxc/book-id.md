# 晋江文学城 - 作品章节

## Coverage
`index-only`

## Route
- Namespace: `jjwxc`
- Namespace Name: `晋江文学城`
- Route Path: `/book/:id?`
- Route Name: `作品章节`
- Example: `/jjwxc/book/7013024`
- URL: `jjwxc.net`
- Language: `zh-CN`
- Categories: `reading`
- Maintainers: `nczitzk`
- Source Location: `book.ts`
- Source Module: `() => import('@/routes/jjwxc/book.ts')`

## Description
_None_

## Parameters
- `id`: 作品 id，可在对应作品页中找到


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
  "example": "/jjwxc/book/7013024",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "book.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/jjwxc/book.ts')",
  "name": "作品章节",
  "parameters": {
    "id": "作品 id，可在对应作品页中找到"
  },
  "path": "/book/:id?",
  "view": 5
}
```
