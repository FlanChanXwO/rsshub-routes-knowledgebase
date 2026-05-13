# 豆瓣 - 热门同城活动

## Coverage
`index-only`

## Route
- Namespace: `douban`
- Namespace Name: `豆瓣`
- Route Path: `/event/hot/:locationId`
- Route Name: `热门同城活动`
- Example: `/douban/event/hot/118172`
- URL: `www.douban.com`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `xyqfer`
- Source Location: `event/hot.ts`
- Source Module: `() => import('@/routes/douban/event/hot.ts')`

## Description
_None_

## Parameters
- `locationId`: 位置 id, [同城首页](https://www.douban.com/location)打开控制台执行 `window.__loc_id__` 获取


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
  "example": "/douban/event/hot/118172",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "event/hot.ts",
  "maintainers": [
    "xyqfer"
  ],
  "module": "() => import('@/routes/douban/event/hot.ts')",
  "name": "热门同城活动",
  "parameters": {
    "locationId": "位置 id, [同城首页](https://www.douban.com/location)打开控制台执行 `window.__loc_id__` 获取"
  },
  "path": "/event/hot/:locationId"
}
```
