# 苏州科技大学 - 教务处

## Coverage
`index-only`

## Route
- Namespace: `usts`
- Namespace Name: `苏州科技大学`
- Route Path: `/jwch/:type?`
- Route Name: `教务处`
- Example: `/usts/jwch`
- URL: `jwch.usts.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `None`
- Source Location: `jwch.ts`
- Source Module: `() => import('@/routes/usts/jwch.ts')`

## Description
| 类型 | 教务动态 | 公告在线 | 选课通知 |
| ---- | -------- | -------- | -------- |
|      | jwdt     | ggzx     | xktz     |

## Parameters
- `type`: 类型，默认为教务动态


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
  "description": "| 类型 | 教务动态 | 公告在线 | 选课通知 |\n| ---- | -------- | -------- | -------- |\n|      | jwdt     | ggzx     | xktz     |",
  "example": "/usts/jwch",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "jwch.ts",
  "maintainers": [],
  "module": "() => import('@/routes/usts/jwch.ts')",
  "name": "教务处",
  "parameters": {
    "type": "类型，默认为教务动态"
  },
  "path": "/jwch/:type?"
}
```
