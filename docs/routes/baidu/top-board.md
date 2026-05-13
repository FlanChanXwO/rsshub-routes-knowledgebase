# 百度 - 热搜榜单

## Coverage
`index-only`

## Route
- Namespace: `baidu`
- Namespace Name: `百度`
- Route Path: `/top/:board?`
- Route Name: `热搜榜单`
- Example: `/baidu/top`
- URL: `www.baidu.com`
- Language: `zh-CN`
- Categories: `other`
- Maintainers: `xyqfer`
- Source Location: `top.tsx`
- Source Module: `() => import('@/routes/baidu/top.tsx')`

## Description
| 热搜榜   | 小说榜 | 电影榜 | 电视剧榜 | 汽车榜 | 游戏榜 |
| -------- | ------ | ------ | -------- | ------ | ------ |
| realtime | novel  | movie  | teleplay | car    | game   |

## Parameters
- `board`: 榜单，默认为 `realtime`


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
    "other"
  ],
  "description": "| 热搜榜   | 小说榜 | 电影榜 | 电视剧榜 | 汽车榜 | 游戏榜 |\n| -------- | ------ | ------ | -------- | ------ | ------ |\n| realtime | novel  | movie  | teleplay | car    | game   |",
  "example": "/baidu/top",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "top.tsx",
  "maintainers": [
    "xyqfer"
  ],
  "module": "() => import('@/routes/baidu/top.tsx')",
  "name": "热搜榜单",
  "parameters": {
    "board": "榜单，默认为 `realtime`"
  },
  "path": "/top/:board?"
}
```
