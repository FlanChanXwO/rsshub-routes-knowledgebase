# 山东大学 - 学生在线（青岛）

## Coverage
`index-only`

## Route
- Namespace: `sdu`
- Namespace Name: `山东大学`
- Route Path: `/qd/xszxqd/:type?`
- Route Name: `学生在线（青岛）`
- Example: `/sdu/qd/xszxqd/xtyw`
- URL: `www.sdu.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `kukeya`
- Source Location: `qd/xszxqd.ts`
- Source Module: `() => import('@/routes/sdu/qd/xszxqd.ts')`

## Description
| 学团通知-研究生 | 学团通知-本科生 | 学团通知-团学 | 学团通知-心理 | 学团要闻
| -------- | -------- |-------- |-------- |-------- |
| xttz-yjs   | xttz-bks  |  xttz-tx  | xttz-xl  | xtyw  |

## Parameters
- `type`: 默认为`xtyw`


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
  "description": "| 学团通知-研究生 | 学团通知-本科生 | 学团通知-团学 | 学团通知-心理 | 学团要闻\n| -------- | -------- |-------- |-------- |-------- |\n| xttz-yjs   | xttz-bks  |  xttz-tx  | xttz-xl  | xtyw  |",
  "example": "/sdu/qd/xszxqd/xtyw",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "qd/xszxqd.ts",
  "maintainers": [
    "kukeya"
  ],
  "module": "() => import('@/routes/sdu/qd/xszxqd.ts')",
  "name": "学生在线（青岛）",
  "parameters": {
    "type": "默认为`xtyw`"
  },
  "path": "/qd/xszxqd/:type?"
}
```
