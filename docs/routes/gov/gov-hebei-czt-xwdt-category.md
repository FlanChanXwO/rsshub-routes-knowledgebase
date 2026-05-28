# Hangzhou People's Government - 财政厅

## Coverage
`index-only`

## Route
- Namespace: `gov`
- Namespace Name: `Hangzhou People's Government`
- Route Path: `/gov/hebei/czt/xwdt/:category?`
- Route Name: `财政厅`
- Example: `/gov/hebei/czt/xwdt`
- URL: `hangzhou.gov.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `nczitzk`
- Source Location: `hebei/czt.ts`
- Source Module: `_None_`

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
  "heat": 0,
  "location": "hebei/czt.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "财政厅",
  "parameters": {
    "category": "分类，见下表，默认为财政动态"
  },
  "path": "/hebei/czt/xwdt/:category?",
  "topFeeds": []
}
```
