# 豆瓣 - 豆瓣电影人

## Coverage
`index-only`

## Route
- Namespace: `douban`
- Namespace Name: `豆瓣`
- Route Path: `/celebrity/:id/:sort?`
- Route Name: `豆瓣电影人`
- Example: `/douban/celebrity/1274261`
- URL: `www.douban.com`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `minimalistrojan`
- Source Location: `other/celebrity.ts`
- Source Module: `() => import('@/routes/douban/other/celebrity.ts')`

## Description
_None_

## Parameters
- `id`: 电影人 id
- `sort`: 排序方式，缺省为 `time`（时间排序），可为 `vote` （评价排序）


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
  "example": "/douban/celebrity/1274261",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "other/celebrity.ts",
  "maintainers": [
    "minimalistrojan"
  ],
  "module": "() => import('@/routes/douban/other/celebrity.ts')",
  "name": "豆瓣电影人",
  "parameters": {
    "id": "电影人 id",
    "sort": "排序方式，缺省为 `time`（时间排序），可为 `vote` （评价排序）"
  },
  "path": "/celebrity/:id/:sort?"
}
```
