# 中国汽车工业协会统计信息网 - 分类

## Coverage
`index-only`

## Route
- Namespace: `auto-stats`
- Namespace Name: `中国汽车工业协会统计信息网`
- Route Path: `/:category?`
- Route Name: `分类`
- Example: `/auto-stats`
- URL: `auto-stats.org.cn`
- Language: `zh-CN`
- Categories: `other`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/auto-stats/index.ts')`

## Description
| 信息快递 | 工作动态 | 专题分析 |
| -------- | -------- | -------- |
| xxkd     | gzdt     | ztfx     |

## Parameters
- `category`: 分类，见下表，默认为信息快递


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
    "other"
  ],
  "description": "| 信息快递 | 工作动态 | 专题分析 |\n| -------- | -------- | -------- |\n| xxkd     | gzdt     | ztfx     |",
  "example": "/auto-stats",
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
    "nczitzk"
  ],
  "module": "() => import('@/routes/auto-stats/index.ts')",
  "name": "分类",
  "parameters": {
    "category": "分类，见下表，默认为信息快递"
  },
  "path": "/:category?"
}
```
