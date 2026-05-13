# 浙江中医药大学 - 药学院

## Coverage
`index-only`

## Route
- Namespace: `zcmu`
- Namespace Name: `浙江中医药大学`
- Route Path: `/yxy/:type?`
- Route Name: `药学院`
- Example: `/zcmu/yxy/0`
- URL: `jwc.zcmu.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `CCraftY`
- Source Location: `yxy/index.ts`
- Source Module: `() => import('@/routes/zcmu/yxy/index.ts')`

## Description
| 通知公告 | 评优评奖 | 文明规范 | 创新创业 | 校园文化 | 心理驿站 | 日常通知 |
| -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| 0        | 1        | 2        | 3        | 4        | 5        | 6        |

## Parameters
- `type`: 模块id


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
  "description": "| 通知公告 | 评优评奖 | 文明规范 | 创新创业 | 校园文化 | 心理驿站 | 日常通知 |\n| -------- | -------- | -------- | -------- | -------- | -------- | -------- |\n| 0        | 1        | 2        | 3        | 4        | 5        | 6        |",
  "example": "/zcmu/yxy/0",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "yxy/index.ts",
  "maintainers": [
    "CCraftY"
  ],
  "module": "() => import('@/routes/zcmu/yxy/index.ts')",
  "name": "药学院",
  "parameters": {
    "type": "模块id"
  },
  "path": "/yxy/:type?"
}
```
