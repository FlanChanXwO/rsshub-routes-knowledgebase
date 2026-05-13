# 上海交通大学 - 教务处通知公告

## Coverage
`index-only`

## Route
- Namespace: `sjtu`
- Namespace Name: `上海交通大学`
- Route Path: `/jwc/:type?`
- Route Name: `教务处通知公告`
- Example: `/sjtu/jwc`
- URL: `www.sjtu.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `SeanChao`
- Source Location: `jwc.ts`
- Source Module: `() => import('@/routes/sjtu/jwc.ts')`

## Description
| 新闻中心 | 通知通告 | 教学运行  | 注册学务 | 研究办 | 教改办 | 综合办 | 语言文字 | 工会与支部 | 通识教育 | 面向学生的通知 |
| -------- | -------- | --------- | -------- | ------ | ------ | ------ | -------- | ---------- | -------- |
| news     | notice   | operation | affairs  | yjb    | jgb    | zhb    | language | party      | ge       | students  |

## Parameters
- `type`: 默认为 notice


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
  "description": "| 新闻中心 | 通知通告 | 教学运行  | 注册学务 | 研究办 | 教改办 | 综合办 | 语言文字 | 工会与支部 | 通识教育 | 面向学生的通知 |\n| -------- | -------- | --------- | -------- | ------ | ------ | ------ | -------- | ---------- | -------- |\n| news     | notice   | operation | affairs  | yjb    | jgb    | zhb    | language | party      | ge       | students  |",
  "example": "/sjtu/jwc",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "jwc.ts",
  "maintainers": [
    "SeanChao"
  ],
  "module": "() => import('@/routes/sjtu/jwc.ts')",
  "name": "教务处通知公告",
  "parameters": {
    "type": "默认为 notice"
  },
  "path": "/jwc/:type?"
}
```
