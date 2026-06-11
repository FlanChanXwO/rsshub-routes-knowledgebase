# 河北省人民政府 - 财政厅

## Coverage
`index-only`

## Route
- Namespace: `gov/hebei`
- Namespace Name: `河北省人民政府`
- Route Path: `/gov/hebei/czt/xwdt/:category?`
- Route Name: `财政厅`
- Example: `/gov/hebei/czt/xwdt`
- URL: `www.hebei.gov.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `nczitzk`
- Source Location: `czt.ts`
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
  "location": "czt.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "财政厅",
  "parameters": {
    "category": "分类，见下表，默认为财政动态"
  },
  "path": "/czt/xwdt/:category?",
  "topFeeds": []
}
```
