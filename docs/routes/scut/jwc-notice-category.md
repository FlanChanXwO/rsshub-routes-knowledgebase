# 华南理工大学 - 教务处通知公告

## Coverage
`index-only`

## Route
- Namespace: `scut`
- Namespace Name: `华南理工大学`
- Route Path: `/jwc/notice/:category?`
- Route Name: `教务处通知公告`
- Example: `/scut/jwc/notice/all`
- URL: `jw.scut.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `imkero`
- Source Location: `jwc/notice.ts`
- Source Module: `() => import('@/routes/scut/jwc/notice.ts')`

## Description
| 全部 | 选课   | 考试 | 实践     | 交流          | 教师    | 信息 |
| ---- | ------ | ---- | -------- | ------------- | ------- | ---- |
| all  | course | exam | practice | communication | teacher | info |

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
  "description": "| 全部 | 选课   | 考试 | 实践     | 交流          | 教师    | 信息 |\n| ---- | ------ | ---- | -------- | ------------- | ------- | ---- |\n| all  | course | exam | practice | communication | teacher | info |",
  "example": "/scut/jwc/notice/all",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "jwc/notice.ts",
  "maintainers": [
    "imkero"
  ],
  "module": "() => import('@/routes/scut/jwc/notice.ts')",
  "name": "教务处通知公告",
  "parameters": {
    "category": "通知分类，默认为 `all`"
  },
  "path": "/jwc/notice/:category?"
}
```
