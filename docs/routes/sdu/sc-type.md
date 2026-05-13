# 山东大学 - 软件学院通知

## Coverage
`index-only`

## Route
- Namespace: `sdu`
- Namespace Name: `山东大学`
- Route Path: `/sc/:type?`
- Route Name: `软件学院通知`
- Example: `/sdu/sc/0`
- URL: `www.sdu.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `Ji4n1ng`
- Source Location: `sc.ts`
- Source Module: `() => import('@/routes/sdu/sc.ts')`

## Description
| 通知公告 | 学术动态 | 本科教育 | 研究生教育 |
| -------- | -------- | -------- | ---------- |
| 0        | 1        | 2        | 3          |

## Parameters
- `type`: 默认为 `0`


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
  "description": "| 通知公告 | 学术动态 | 本科教育 | 研究生教育 |\n| -------- | -------- | -------- | ---------- |\n| 0        | 1        | 2        | 3          |",
  "example": "/sdu/sc/0",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "sc.ts",
  "maintainers": [
    "Ji4n1ng"
  ],
  "module": "() => import('@/routes/sdu/sc.ts')",
  "name": "软件学院通知",
  "parameters": {
    "type": "默认为 `0`"
  },
  "path": "/sc/:type?"
}
```
