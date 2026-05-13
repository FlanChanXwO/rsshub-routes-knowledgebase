# 前瞻网 - 文章列表

## Coverage
`index-only`

## Route
- Namespace: `qianzhan`
- Namespace Name: `前瞻网`
- Route Path: `/analyst/column/:type?`
- Route Name: `文章列表`
- Example: `/qianzhan/analyst/column/all`
- URL: `qianzhan.com`
- Language: `zh-CN`
- Categories: `finance`
- Maintainers: `moke8`
- Source Location: `column.ts`
- Source Module: `() => import('@/routes/qianzhan/column.ts')`

## Description
| 全部 | 研究员专栏 | 规划师专栏 | 观察家专栏 |
| ---- | ---------- | ---------- | ---------- |
| all  | 220        | 627        | 329        |

## Parameters
- `type`: 分类，见下表


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
    "finance"
  ],
  "description": "| 全部 | 研究员专栏 | 规划师专栏 | 观察家专栏 |\n| ---- | ---------- | ---------- | ---------- |\n| all  | 220        | 627        | 329        |",
  "example": "/qianzhan/analyst/column/all",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "column.ts",
  "maintainers": [
    "moke8"
  ],
  "module": "() => import('@/routes/qianzhan/column.ts')",
  "name": "文章列表",
  "parameters": {
    "type": "分类，见下表"
  },
  "path": "/analyst/column/:type?"
}
```
