# 南京师范大学 - 教务通知

## Coverage
`index-only`

## Route
- Namespace: `njnu`
- Namespace Name: `南京师范大学`
- Route Path: `/jwc/:type`
- Route Name: `教务通知`
- Example: `/njnu/jwc/xstz`
- URL: `ceai.njnu.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `Shujakuinkuraudo`
- Source Location: `jwc/jwc.ts`
- Source Module: `() => import('@/routes/njnu/jwc/jwc.ts')`

## Description
| 教师通知 | 新闻动态 | 学生通知 |
| -------- | -------- | -------- |
| jstz     | xwdt     | xstz     |

## Parameters
- `type`: 分类名


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
  "description": "| 教师通知 | 新闻动态 | 学生通知 |\n| -------- | -------- | -------- |\n| jstz     | xwdt     | xstz     |",
  "example": "/njnu/jwc/xstz",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "jwc/jwc.ts",
  "maintainers": [
    "Shujakuinkuraudo"
  ],
  "module": "() => import('@/routes/njnu/jwc/jwc.ts')",
  "name": "教务通知",
  "parameters": {
    "type": "分类名"
  },
  "path": "/jwc/:type"
}
```
