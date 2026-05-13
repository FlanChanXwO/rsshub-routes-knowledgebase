# 武汉纺织大学 - 信息门户公告

## Coverage
`index-only`

## Route
- Namespace: `wtu`
- Namespace Name: `武汉纺织大学`
- Route Path: `/:type`
- Route Name: `信息门户公告`
- Example: `/wtu/2`
- URL: `wtu.91wllm.com`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `loyio`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/wtu/index.ts')`

## Description
| 公告类型 | 通知公告 | 教务信息 | 科研动态 |
| -------- | -------- | -------- | -------- |
| 参数     | 1        | 2        | 3        |

## Parameters
- `type`: 公告类型，详见表格


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
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
  "description": "| 公告类型 | 通知公告 | 教务信息 | 科研动态 |\n| -------- | -------- | -------- | -------- |\n| 参数     | 1        | 2        | 3        |",
  "example": "/wtu/2",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.ts",
  "maintainers": [
    "loyio"
  ],
  "module": "() => import('@/routes/wtu/index.ts')",
  "name": "信息门户公告",
  "parameters": {
    "type": "公告类型，详见表格"
  },
  "path": "/:type"
}
```
