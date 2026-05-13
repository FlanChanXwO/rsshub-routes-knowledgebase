# 浙江中医药大学 - 教务处

## Coverage
`index-only`

## Route
- Namespace: `zcmu`
- Namespace Name: `浙江中医药大学`
- Route Path: `/jwc/:type?`
- Route Name: `教务处`
- Example: `/zcmu/jwc/1`
- URL: `jwc.zcmu.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `CCraftY`
- Source Location: `jwc/index.ts`
- Source Module: `() => import('@/routes/zcmu/jwc/index.ts')`

## Description
| 教务管理 | 成绩管理 | 学籍管理 | 考试管理 | 选课管理 | 排课管理 |
| -------- | -------- | -------- | -------- | -------- | -------- |
| 0        | 1        | 2        | 3        | 4        | 5        |

## Parameters
- `type`: 通知模块id


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
  "description": "| 教务管理 | 成绩管理 | 学籍管理 | 考试管理 | 选课管理 | 排课管理 |\n| -------- | -------- | -------- | -------- | -------- | -------- |\n| 0        | 1        | 2        | 3        | 4        | 5        |",
  "example": "/zcmu/jwc/1",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "jwc/index.ts",
  "maintainers": [
    "CCraftY"
  ],
  "module": "() => import('@/routes/zcmu/jwc/index.ts')",
  "name": "教务处",
  "parameters": {
    "type": "通知模块id"
  },
  "path": "/jwc/:type?"
}
```
