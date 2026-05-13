# 南方都市报 - 奥一网

## Coverage
`index-only`

## Route
- Namespace: `oeeee`
- Namespace Name: `南方都市报`
- Route Path: `/web/:channel`
- Route Name: `奥一网`
- Example: `/oeeee/web/170`
- URL: `oeeee.com`
- Language: `zh-CN`
- Categories: `traditional-media`
- Maintainers: `TimWu007`
- Source Location: `web.ts`
- Source Module: `() => import('@/routes/oeeee/web.ts')`

## Description
-   若在桌面端打开奥一网栏目页（如 `https://www.oeeee.com/api/channel.php?s=/index/index/channel/gz`），可查看该页源代码，搜索 `OECID`。
  -   若在移动端打开奥一网栏目页（格式例：`https://m.oeeee.com/m.php?s=/m2/channel&channel_id=169`），即可从 url 中获取。需注意的是，如果该栏目页的 url 格式为 `https://m.oeeee.com/detailChannel_indexData.html?channel_id=266` ，则 `266` 并非为本路由可用的频道 ID，建议从桌面端获取。

## Parameters
- `channel`: 频道 ID


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
    "traditional-media"
  ],
  "description": "-   若在桌面端打开奥一网栏目页（如 `https://www.oeeee.com/api/channel.php?s=/index/index/channel/gz`），可查看该页源代码，搜索 `OECID`。\n  -   若在移动端打开奥一网栏目页（格式例：`https://m.oeeee.com/m.php?s=/m2/channel&channel_id=169`），即可从 url 中获取。需注意的是，如果该栏目页的 url 格式为 `https://m.oeeee.com/detailChannel_indexData.html?channel_id=266` ，则 `266` 并非为本路由可用的频道 ID，建议从桌面端获取。",
  "example": "/oeeee/web/170",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "web.ts",
  "maintainers": [
    "TimWu007"
  ],
  "module": "() => import('@/routes/oeeee/web.ts')",
  "name": "奥一网",
  "parameters": {
    "channel": "频道 ID"
  },
  "path": "/web/:channel"
}
```
