# 西安财经大学 - 教务处

## Coverage
`index-only`

## Route
- Namespace: `xaufe`
- Namespace Name: `西安财经大学`
- Route Path: `/jiaowu/:category?`
- Route Name: `教务处`
- Example: `/xaufe/jiaowu/tzgg`
- URL: `jiaowu.xaufe.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `shaokeyibb`
- Source Location: `jiaowu.ts`
- Source Module: `() => import('@/routes/xaufe/jiaowu.ts')`

## Description
| 通知公告 |
| :------: |
|   tzgg   |

## Parameters
- `category`: 分类，默认为通知公告


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
  "description": "| 通知公告 |\n| :------: |\n|   tzgg   |",
  "example": "/xaufe/jiaowu/tzgg",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "jiaowu.ts",
  "maintainers": [
    "shaokeyibb"
  ],
  "module": "() => import('@/routes/xaufe/jiaowu.ts')",
  "name": "教务处",
  "parameters": {
    "category": "分类，默认为通知公告"
  },
  "path": "/jiaowu/:category?"
}
```
