# 东华大学 - 研究生招生信息

## Coverage
`index-only`

## Route
- Namespace: `dhu`
- Namespace Name: `东华大学`
- Route Path: `/yjs/zs/:type?`
- Route Name: `研究生招生信息`
- Example: `/dhu/yjs/zs/master`
- URL: `www.dhu.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `fox2049`
- Source Location: `yjs/zs.ts`
- Source Module: `() => import('@/routes/dhu/yjs/zs.ts')`

## Description
| 博士招生 | 硕士招生 |
| -------- | -------- |
| doctor   | master   |

## Parameters
- `type`: 默认为 `master`


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
  "description": "| 博士招生 | 硕士招生 |\n| -------- | -------- |\n| doctor   | master   |",
  "example": "/dhu/yjs/zs/master",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "yjs/zs.ts",
  "maintainers": [
    "fox2049"
  ],
  "module": "() => import('@/routes/dhu/yjs/zs.ts')",
  "name": "研究生招生信息",
  "parameters": {
    "type": "默认为 `master`"
  },
  "path": "/yjs/zs/:type?"
}
```
