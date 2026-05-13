# 小黑盒 - 游戏折扣

## Coverage
`index-only`

## Route
- Namespace: `xiaoheihe`
- Namespace Name: `小黑盒`
- Route Path: `/discount/:platform`
- Route Name: `游戏折扣`
- Example: `/xiaoheihe/discount/pc`
- URL: `xiaoheihe.cn`
- Language: `zh-CN`
- Categories: `game`
- Maintainers: `tssujt`
- Source Location: `discount.ts`
- Source Module: `() => import('@/routes/xiaoheihe/discount.ts')`

## Description
| PC  | Switch  | PSN   | Xbox |
| ----- | ------ | ----- | ----- |
| pc    | switch | psn   | xbox  |

## Parameters
- `platform`: 平台分类，见下表


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
    "game"
  ],
  "description": "| PC  | Switch  | PSN   | Xbox |\n| ----- | ------ | ----- | ----- |\n| pc    | switch | psn   | xbox  |",
  "example": "/xiaoheihe/discount/pc",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "discount.ts",
  "maintainers": [
    "tssujt"
  ],
  "module": "() => import('@/routes/xiaoheihe/discount.ts')",
  "name": "游戏折扣",
  "parameters": {
    "platform": "平台分类，见下表"
  },
  "path": "/discount/:platform"
}
```
