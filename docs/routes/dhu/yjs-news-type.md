# 东华大学 - 研究生院通知

## Coverage
`index-only`

## Route
- Namespace: `dhu`
- Namespace Name: `东华大学`
- Route Path: `/yjs/news/:type?`
- Route Name: `研究生院通知`
- Example: `/dhu/yjs/news/class`
- URL: `www.dhu.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `fox2049`
- Source Location: `yjs/news.ts`
- Source Module: `() => import('@/routes/dhu/yjs/news.ts')`

## Description
| 新闻动态 | 通知公告 | 选课考试 |
| -------- | -------- | -------- |
| trend    | notice   | class    |

## Parameters
- `type`: 默认为 `class`


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
  "description": "| 新闻动态 | 通知公告 | 选课考试 |\n| -------- | -------- | -------- |\n| trend    | notice   | class    |",
  "example": "/dhu/yjs/news/class",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "yjs/news.ts",
  "maintainers": [
    "fox2049"
  ],
  "module": "() => import('@/routes/dhu/yjs/news.ts')",
  "name": "研究生院通知",
  "parameters": {
    "type": "默认为 `class`"
  },
  "path": "/yjs/news/:type?"
}
```
