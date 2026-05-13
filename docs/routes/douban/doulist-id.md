# 豆瓣 - 豆瓣豆列

## Coverage
`index-only`

## Route
- Namespace: `douban`
- Namespace Name: `豆瓣`
- Route Path: `/doulist/:id`
- Route Name: `豆瓣豆列`
- Example: `/douban/doulist/37716774`
- URL: `www.douban.com`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `LogicJake, honue`
- Source Location: `other/doulist.ts`
- Source Module: `() => import('@/routes/douban/other/doulist.ts')`

## Description
_None_

## Parameters
- `id`: 豆列id


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
    "social-media"
  ],
  "example": "/douban/doulist/37716774",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "other/doulist.ts",
  "maintainers": [
    "LogicJake",
    "honue"
  ],
  "module": "() => import('@/routes/douban/other/doulist.ts')",
  "name": "豆瓣豆列",
  "parameters": {
    "id": "豆列id"
  },
  "path": "/doulist/:id"
}
```
