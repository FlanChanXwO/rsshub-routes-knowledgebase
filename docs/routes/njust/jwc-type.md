# 南京理工大学 - 教务处

## Coverage
`index-only`

## Route
- Namespace: `njust`
- Namespace Name: `南京理工大学`
- Route Path: `/jwc/:type?`
- Route Name: `教务处`
- Example: `/njust/jwc/xstz`
- URL: `jwc.njust.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `MilkShakeYoung, jasongzy`
- Source Location: `jwc.ts`
- Source Module: `() => import('@/routes/njust/jwc.ts')`

## Description
| 教师通知 | 学生通知 | 新闻 | 学院动态 |
| -------- | -------- | ---- | -------- |
| jstz     | xstz     | xw   | xydt     |

## Parameters
- `type`: 分类名，见下表，默认为学生通知


## Features
- `requireConfig`: false
- `requirePuppeteer`: true
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
  "description": "| 教师通知 | 学生通知 | 新闻 | 学院动态 |\n| -------- | -------- | ---- | -------- |\n| jstz     | xstz     | xw   | xydt     |",
  "example": "/njust/jwc/xstz",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "jwc.ts",
  "maintainers": [
    "MilkShakeYoung",
    "jasongzy"
  ],
  "module": "() => import('@/routes/njust/jwc.ts')",
  "name": "教务处",
  "parameters": {
    "type": "分类名，见下表，默认为学生通知"
  },
  "path": "/jwc/:type?"
}
```
