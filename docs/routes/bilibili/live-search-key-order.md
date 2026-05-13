# 哔哩哔哩 bilibili - 直播搜索

## Coverage
`index-only`

## Route
- Namespace: `bilibili`
- Namespace Name: `哔哩哔哩 bilibili`
- Route Path: `/live/search/:key/:order`
- Route Name: `直播搜索`
- Example: `/bilibili/live/search/dota/online`
- URL: `www.bilibili.com`
- Language: `zh-CN`
- Categories: `live`
- Maintainers: `Qixingchen`
- Source Location: `live-search.ts`
- Source Module: `() => import('@/routes/bilibili/live-search.ts')`

## Description
_None_

## Parameters
- `key`: 搜索关键字
- `order`: 排序方式, live_time 开播时间, online 人气


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
    "live"
  ],
  "example": "/bilibili/live/search/dota/online",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "live-search.ts",
  "maintainers": [
    "Qixingchen"
  ],
  "module": "() => import('@/routes/bilibili/live-search.ts')",
  "name": "直播搜索",
  "parameters": {
    "key": "搜索关键字",
    "order": "排序方式, live_time 开播时间, online 人气"
  },
  "path": "/live/search/:key/:order"
}
```
