# 同济大学 - 经济与管理学院通知

## Coverage
`index-only`

## Route
- Namespace: `tongji`
- Namespace Name: `同济大学`
- Route Path: `/sem/:type?`
- Route Name: `经济与管理学院通知`
- Example: `/tongji/sem/notice`
- URL: `sem.tongji.edu.cn/semch`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `sitdownkevin`
- Source Location: `sem/notice.ts`
- Source Module: `() => import('@/routes/tongji/sem/notice.ts')`

## Description
| 学院通知 | 招生通知 | 学术观点 | 新闻 | 活动 | 视点 | 教师与行政人员招聘 |
| -------- | -------------- | ------------------ | ---- | ---------- | --------- | ------------------ |
| notice   | enrollment     | academic-paper     | news | events     | focus     | collegerecruitment |

## Parameters
- `type`: 通知类型，默认为 `notice`


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
  "description": "| 学院通知 | 招生通知 | 学术观点 | 新闻 | 活动 | 视点 | 教师与行政人员招聘 |\n| -------- | -------------- | ------------------ | ---- | ---------- | --------- | ------------------ |\n| notice   | enrollment     | academic-paper     | news | events     | focus     | collegerecruitment |\n",
  "example": "/tongji/sem/notice",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "sem/notice.ts",
  "maintainers": [
    "sitdownkevin"
  ],
  "module": "() => import('@/routes/tongji/sem/notice.ts')",
  "name": "经济与管理学院通知",
  "parameters": {
    "type": "通知类型，默认为 `notice`"
  },
  "path": "/sem/:type?",
  "url": "sem.tongji.edu.cn/semch"
}
```
