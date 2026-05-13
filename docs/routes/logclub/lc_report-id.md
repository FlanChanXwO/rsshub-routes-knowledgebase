# 罗戈网 - 报告

## Coverage
`index-only`

## Route
- Namespace: `logclub`
- Namespace Name: `罗戈网`
- Route Path: `/lc_report/:id?`
- Route Name: `报告`
- Example: `/logclub/lc_report`
- URL: `logclub.com`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `report.ts`
- Source Module: `() => import('@/routes/logclub/report.ts')`

## Description
| 罗戈研究出品 | 物流报告       | 绿色双碳报告          |
| ------------ | -------------- | --------------------- |
| Report       | IndustryReport | GreenDualCarbonReport |

## Parameters
- `id`: 报告 id，见下表，默认为罗戈研究出品


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
    "new-media"
  ],
  "description": "| 罗戈研究出品 | 物流报告       | 绿色双碳报告          |\n| ------------ | -------------- | --------------------- |\n| Report       | IndustryReport | GreenDualCarbonReport |",
  "example": "/logclub/lc_report",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "report.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/logclub/report.ts')",
  "name": "报告",
  "parameters": {
    "id": "报告 id，见下表，默认为罗戈研究出品"
  },
  "path": [
    "/lc_report/:id?",
    "/report/:id?"
  ]
}
```
