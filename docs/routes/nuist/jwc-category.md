# 南京信息工程大学 - 教务处

## Coverage
`index-only`

## Route
- Namespace: `nuist`
- Namespace Name: `南京信息工程大学`
- Route Path: `/jwc/:category?`
- Route Name: `教务处`
- Example: `/nuist/jwc/jxyw`
- URL: `bulletin.nuist.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `gylidian`
- Source Location: `jwc.ts`
- Source Module: `() => import('@/routes/nuist/jwc.ts')`

## Description
| 教学要闻 | 学院教学 | 教务管理 | 教学研究 | 教务管理 | 教材建设 | 考试中心 |
| -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| jxyw     | xyjx     | jwgl     | jxyj     | sjjx     | jcjs     | kszx     |

## Parameters
- `category`: 默认为教学要闻


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
  "description": "| 教学要闻 | 学院教学 | 教务管理 | 教学研究 | 教务管理 | 教材建设 | 考试中心 |\n| -------- | -------- | -------- | -------- | -------- | -------- | -------- |\n| jxyw     | xyjx     | jwgl     | jxyj     | sjjx     | jcjs     | kszx     |",
  "example": "/nuist/jwc/jxyw",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "jwc.ts",
  "maintainers": [
    "gylidian"
  ],
  "module": "() => import('@/routes/nuist/jwc.ts')",
  "name": "教务处",
  "parameters": {
    "category": "默认为教学要闻"
  },
  "path": "/jwc/:category?"
}
```
