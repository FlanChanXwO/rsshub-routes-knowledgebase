# 山东大学 - 材料科学与工程学院通知

## Coverage
`index-only`

## Route
- Namespace: `sdu`
- Namespace Name: `山东大学`
- Route Path: `/cmse/:type?`
- Route Name: `材料科学与工程学院通知`
- Example: `/sdu/cmse/0`
- URL: `www.sdu.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `Ji4n1ng`
- Source Location: `cmse.ts`
- Source Module: `() => import('@/routes/sdu/cmse.ts')`

## Description
| 通知公告 | 学院新闻 | 本科生教育 | 研究生教育 | 学术动态 |
| -------- | -------- | ---------- | ---------- | -------- |
| 0        | 1        | 2          | 3          | 4        |

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
  "description": "| 通知公告 | 学院新闻 | 本科生教育 | 研究生教育 | 学术动态 |\n| -------- | -------- | ---------- | ---------- | -------- |\n| 0        | 1        | 2          | 3          | 4        |",
  "example": "/sdu/cmse/0",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "cmse.ts",
  "maintainers": [
    "Ji4n1ng"
  ],
  "module": "() => import('@/routes/sdu/cmse.ts')",
  "name": "材料科学与工程学院通知",
  "parameters": {
    "type": "默认为 `0`"
  },
  "path": "/cmse/:type?"
}
```
