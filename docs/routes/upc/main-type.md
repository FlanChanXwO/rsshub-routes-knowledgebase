# 中国石油大学（华东） - 主页

## Coverage
`index-only`

## Route
- Namespace: `upc`
- Namespace Name: `中国石油大学（华东）`
- Route Path: `/main/:type`
- Route Name: `主页`
- Example: `/upc/main/notice`
- URL: `computer.upc.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `Veagau`
- Source Location: `main.ts`
- Source Module: `() => import('@/routes/upc/main.ts')`

## Description
| 通知公告 | 学术动态 |
| -------- | -------- |
| notice   | scholar  |

## Parameters
- `type`: 分类，见下表


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
  "description": "| 通知公告 | 学术动态 |\n| -------- | -------- |\n| notice   | scholar  |",
  "example": "/upc/main/notice",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "main.ts",
  "maintainers": [
    "Veagau"
  ],
  "module": "() => import('@/routes/upc/main.ts')",
  "name": "主页",
  "parameters": {
    "type": "分类，见下表"
  },
  "path": "/main/:type"
}
```
