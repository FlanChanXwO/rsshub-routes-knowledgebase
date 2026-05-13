# 华南理工大学 - 教务处学院通知

## Coverage
`index-only`

## Route
- Namespace: `scut`
- Namespace Name: `华南理工大学`
- Route Path: `/jwc/school/:category?`
- Route Name: `教务处学院通知`
- Example: `/scut/jwc/school/all`
- URL: `jw.scut.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `imkero, Rongronggg9`
- Source Location: `jwc/school.ts`
- Source Module: `() => import('@/routes/scut/jwc/school.ts')`

## Description
| 全部 | 选课   | 考试 | 信息 |
| ---- | ------ | ---- | ---- |
| all  | course | exam | info |

## Parameters
- `category`: 通知分类，默认为 `all`


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
  "description": "| 全部 | 选课   | 考试 | 信息 |\n| ---- | ------ | ---- | ---- |\n| all  | course | exam | info |",
  "example": "/scut/jwc/school/all",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "jwc/school.ts",
  "maintainers": [
    "imkero",
    "Rongronggg9"
  ],
  "module": "() => import('@/routes/scut/jwc/school.ts')",
  "name": "教务处学院通知",
  "parameters": {
    "category": "通知分类，默认为 `all`"
  },
  "path": "/jwc/school/:category?"
}
```
