# 国家能源局 - 财政厅

## Coverage
`index-only`

## Route
- Namespace: `gov`
- Namespace Name: `国家能源局`
- Route Path: `/hebei/czt/xwdt/:category?`
- Route Name: `财政厅`
- Example: `/gov/hebei/czt/xwdt`
- URL: `www.nea.gov.cn`
- Language: `zh-CN`
- Categories: `government`
- Maintainers: `nczitzk`
- Source Location: `hebei/czt.ts`
- Source Module: `() => import('@/routes/gov/hebei/czt.ts')`

## Description
| 财政动态 | 综合新闻 | 通知公告 |
| -------- | -------- | -------- |
| gzdt     | zhxw     | tzgg     |

## Parameters
- `category`: 分类，见下表，默认为财政动态


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
    "government"
  ],
  "description": "| 财政动态 | 综合新闻 | 通知公告 |\n| -------- | -------- | -------- |\n| gzdt     | zhxw     | tzgg     |",
  "example": "/gov/hebei/czt/xwdt",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "hebei/czt.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/gov/hebei/czt.ts')",
  "name": "财政厅",
  "parameters": {
    "category": "分类，见下表，默认为财政动态"
  },
  "path": "/hebei/czt/xwdt/:category?"
}
```
