# 中国石油大学（华东） - 计算机科学与技术学院

## Coverage
`index-only`

## Route
- Namespace: `upc`
- Namespace Name: `中国石油大学（华东）`
- Route Path: `/jsj/:type`
- Route Name: `计算机科学与技术学院`
- Example: `/upc/jsj/news`
- URL: `computer.upc.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `Veagau`
- Source Location: `jsj.ts`
- Source Module: `() => import('@/routes/upc/jsj.ts')`

## Description
| 学院新闻 | 学术关注 | 学工动态 | 通知公告 |
| -------- | -------- | -------- | -------- |
| news     | scholar  | states   | notice   |

## Parameters
- `type`: 分类，见下表


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
  "description": "| 学院新闻 | 学术关注 | 学工动态 | 通知公告 |\n| -------- | -------- | -------- | -------- |\n| news     | scholar  | states   | notice   |",
  "example": "/upc/jsj/news",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "jsj.ts",
  "maintainers": [
    "Veagau"
  ],
  "module": "() => import('@/routes/upc/jsj.ts')",
  "name": "计算机科学与技术学院",
  "parameters": {
    "type": "分类，见下表"
  },
  "path": "/jsj/:type"
}
```
