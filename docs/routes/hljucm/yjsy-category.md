# 黑龙江中医药大学 - 研究生院

## Coverage
`index-only`

## Route
- Namespace: `hljucm`
- Namespace Name: `黑龙江中医药大学`
- Route Path: `/yjsy/:category?`
- Route Name: `研究生院`
- Example: `/hljucm/yjsy`
- URL: `yjsy.hljucm.net`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `nczitzk`
- Source Location: `yjsy.ts`
- Source Module: `() => import('@/routes/hljucm/yjsy.ts')`

## Description
| 新闻动态 | 通知公告 |
| -------- | -------- |
| xwdt     | tzgg     |

## Parameters
- `category`: 分类, 见下表，默认为新闻动态


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
  "description": "| 新闻动态 | 通知公告 |\n| -------- | -------- |\n| xwdt     | tzgg     |",
  "example": "/hljucm/yjsy",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "yjsy.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/hljucm/yjsy.ts')",
  "name": "研究生院",
  "parameters": {
    "category": "分类, 见下表，默认为新闻动态"
  },
  "path": "/yjsy/:category?"
}
```
