# 哔哩哔哩 bilibili - 直播分区

## Coverage
`index-only`

## Route
- Namespace: `bilibili`
- Namespace Name: `哔哩哔哩 bilibili`
- Route Path: `/live/area/:areaID/:order`
- Route Name: `直播分区`
- Example: `/bilibili/live/area/207/online`
- URL: `www.bilibili.com`
- Language: `zh-CN`
- Categories: `live`
- Maintainers: `Qixingchen`
- Source Location: `live-area.ts`
- Source Module: `() => import('@/routes/bilibili/live-area.ts')`

## Description
::: warning
  由于接口未提供开播时间，如果直播间未更换标题与分区，将视为一次。如果直播间更换分区与标题，将视为另一项
:::

## Parameters
- `areaID`: 分区 ID 分区增删较多, 可通过 [分区列表](https://api.live.bilibili.com/room/v1/Area/getList) 查询
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
  "description": "::: warning\n  由于接口未提供开播时间，如果直播间未更换标题与分区，将视为一次。如果直播间更换分区与标题，将视为另一项\n:::",
  "example": "/bilibili/live/area/207/online",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "live-area.ts",
  "maintainers": [
    "Qixingchen"
  ],
  "module": "() => import('@/routes/bilibili/live-area.ts')",
  "name": "直播分区",
  "parameters": {
    "areaID": "分区 ID 分区增删较多, 可通过 [分区列表](https://api.live.bilibili.com/room/v1/Area/getList) 查询",
    "order": "排序方式, live_time 开播时间, online 人气"
  },
  "path": "/live/area/:areaID/:order"
}
```
