# 财联社 - 深度

## Coverage
`index-only`

## Route
- Namespace: `cls`
- Namespace Name: `财联社`
- Route Path: `/depth/:category?`
- Route Name: `深度`
- Example: `/cls/depth/1000`
- URL: `cls.cn`
- Language: `zh-CN`
- Categories: `finance`
- Maintainers: `nczitzk`
- Source Location: `depth.ts`
- Source Module: `() => import('@/routes/cls/depth.ts')`

## Description
| 头条 | 股市 | 港股 | 环球 | 公司 | 券商 | 基金 | 地产 | 金融 | 汽车 | 科创 | 创业版 | 品见 | 期货 | 投教 |
| ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ------ | ---- | ---- | ---- |
| 1000 | 1003 | 1135 | 1007 | 1005 | 1118 | 1110 | 1006 | 1032 | 1119 | 1111 | 1127   | 1160 | 1124 | 1176 |

## Parameters
- `category`: 分类代码，可在首页导航栏的目标网址 URL 中找到


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
  "description": "| 头条 | 股市 | 港股 | 环球 | 公司 | 券商 | 基金 | 地产 | 金融 | 汽车 | 科创 | 创业版 | 品见 | 期货 | 投教 |\n| ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ------ | ---- | ---- | ---- |\n| 1000 | 1003 | 1135 | 1007 | 1005 | 1118 | 1110 | 1006 | 1032 | 1119 | 1111 | 1127   | 1160 | 1124 | 1176 |",
  "example": "/cls/depth/1000",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "depth.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/cls/depth.ts')",
  "name": "深度",
  "parameters": {
    "category": "分类代码，可在首页导航栏的目标网址 URL 中找到"
  },
  "path": "/depth/:category?"
}
```
