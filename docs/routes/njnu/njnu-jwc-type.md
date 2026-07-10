# 南京师范大学 - 教务通知

## Coverage
`index-only`

## Route
- Namespace: `njnu`
- Namespace Name: `南京师范大学`
- Route Path: `/njnu/jwc/:type`
- Route Name: `教务通知`
- Example: `/njnu/jwc/xstz`
- URL: `ceai.njnu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `Shujakuinkuraudo`
- Source Location: `jwc/jwc.ts`
- Source Module: `_None_`

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
  "heat": 0,
  "location": "jwc/jwc.ts",
  "maintainers": [
    "Shujakuinkuraudo"
  ],
  "name": "教务通知",
  "parameters": {
    "type": "分类名"
  },
  "path": "/jwc/:type",
  "topFeeds": []
}
```
