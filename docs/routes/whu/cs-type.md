# 武汉大学 - 计算机学院公告

## Coverage
`index-only`

## Route
- Namespace: `whu`
- Namespace Name: `武汉大学`
- Route Path: `/cs/:type`
- Route Name: `计算机学院公告`
- Example: `/whu/cs/2`
- URL: `cs.whu.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `ttyfly`
- Source Location: `cs.ts`
- Source Module: `() => import('@/routes/whu/cs.ts')`

## Description
| 公告类型 | 学院新闻 | 学术交流 | 通知公告 | 科研进展 |
| -------- | -------- | -------- | -------- | -------- |
| 参数     | 0        | 1        | 2        | 3        |

## Parameters
- `type`: 公告类型，详见表格


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
    "university"
  ],
  "description": "| 公告类型 | 学院新闻 | 学术交流 | 通知公告 | 科研进展 |\n| -------- | -------- | -------- | -------- | -------- |\n| 参数     | 0        | 1        | 2        | 3        |",
  "example": "/whu/cs/2",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "cs.ts",
  "maintainers": [
    "ttyfly"
  ],
  "module": "() => import('@/routes/whu/cs.ts')",
  "name": "计算机学院公告",
  "parameters": {
    "type": "公告类型，详见表格"
  },
  "path": "/cs/:type"
}
```
