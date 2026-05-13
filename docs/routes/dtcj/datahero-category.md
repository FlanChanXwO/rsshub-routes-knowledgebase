# DT 财经 - 数据侠专栏

## Coverage
`index-only`

## Route
- Namespace: `dtcj`
- Namespace Name: `DT 财经`
- Route Path: `/datahero/:category?`
- Route Name: `数据侠专栏`
- Example: `/dtcj/datahero`
- URL: `dtcj.com`
- Language: `zh-CN`
- Categories: `finance`
- Maintainers: `nczitzk`
- Source Location: `datahero.ts`
- Source Module: `() => import('@/routes/dtcj/datahero.ts')`

## Description
| 侠创 | 纽约数据科学学院 | RS 实验所 | 阿里云天池 |
| ---- | ---------------- | --------- | ---------- |
| 5    | 6                | 9         | 10         |

## Parameters
- `category`: 分类，见下表，默认为全部


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
  "description": "| 侠创 | 纽约数据科学学院 | RS 实验所 | 阿里云天池 |\n| ---- | ---------------- | --------- | ---------- |\n| 5    | 6                | 9         | 10         |",
  "example": "/dtcj/datahero",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "datahero.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/dtcj/datahero.ts')",
  "name": "数据侠专栏",
  "parameters": {
    "category": "分类，见下表，默认为全部"
  },
  "path": "/datahero/:category?"
}
```
