# 重庆文理学院 - 通知公告

## Coverage
`index-only`

## Route
- Namespace: `cqwu`
- Namespace Name: `重庆文理学院`
- Route Path: `/news/:type?`
- Route Name: `通知公告`
- Example: `/cqwu/news/academiceve`
- URL: `www.cqwu.net`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `Fatpandac`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/cqwu/index.ts')`

## Description
| 通知公告 | 学术活动公告 |
| -------- | ------------ |
| notify   | academiceve  |

## Parameters
- `type`: 可选，默认为 academiceve


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
  "description": "| 通知公告 | 学术活动公告 |\n| -------- | ------------ |\n| notify   | academiceve  |",
  "example": "/cqwu/news/academiceve",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.ts",
  "maintainers": [
    "Fatpandac"
  ],
  "module": "() => import('@/routes/cqwu/index.ts')",
  "name": "通知公告",
  "parameters": {
    "type": "可选，默认为 academiceve "
  },
  "path": "/news/:type?"
}
```
