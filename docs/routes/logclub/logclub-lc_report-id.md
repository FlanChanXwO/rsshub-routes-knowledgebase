# 罗戈网 - 报告

## Coverage
`index-only`

## Route
- Namespace: `logclub`
- Namespace Name: `罗戈网`
- Route Path: `/logclub/lc_report/:id?`
- Route Name: `报告`
- Example: `/logclub/lc_report`
- URL: `logclub.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `report.ts`
- Source Module: `_None_`

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
  "heat": 3,
  "location": "report.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "报告",
  "parameters": {
    "id": "报告 id，见下表，默认为罗戈研究出品"
  },
  "path": [
    "/lc_report/:id?",
    "/report/:id?"
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "罗戈网（www.logclub.com）-物流商业伙伴, - Powered by RSSHub",
      "errorAt": "2025-10-01T05:58:34.062Z",
      "errorMessage": "Cannot read properties of undefined (reading 'slice')\n",
      "id": "122905311734382592",
      "image": "https://www.logclub.com/public/static/front/images/pc_logo.svg",
      "ownerUserId": null,
      "siteUrl": "https://www.logclub.com/lc_report",
      "title": "【罗戈网】 报告",
      "type": "feed",
      "url": "rsshub://logclub/lc_report"
    }
  ]
}
```
