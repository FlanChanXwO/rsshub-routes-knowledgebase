# 深圳市罗湖区人民政府 - 政府公开信息

## Coverage
`index-only`

## Route
- Namespace: `gov`
- Namespace Name: `深圳市罗湖区人民政府`
- Route Path: `/gov/sichuan/deyang/govpublicinfo/:countyName/:infoType?`
- Route Name: `政府公开信息`
- Example: `/gov/sichuan/deyang/govpublicinfo/绵竹市`
- URL: `www.szlh.gov.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `zytomorrow`
- Source Location: `sichuan/deyang/govpublicinfo.tsx`
- Source Module: `_None_`

## Description
| 法定主动内容 | 公示公告 |
| :----------: | :------: |
|    fdzdnr    |   gsgg   |

## Parameters
- `countyName`: 区县名（**其他区县整改中，暂时只支持`绵竹市`**）。德阳市、绵竹市、广汉市、什邡市、中江县、罗江区、旌阳区、高新区
- `infoType`: 信息类型。默认值:fdzdnr-“法定主动内容”


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
  "description": "| 法定主动内容 | 公示公告 |\n| :----------: | :------: |\n|    fdzdnr    |   gsgg   |",
  "example": "/gov/sichuan/deyang/govpublicinfo/绵竹市",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "sichuan/deyang/govpublicinfo.tsx",
  "maintainers": [
    "zytomorrow"
  ],
  "name": "政府公开信息",
  "parameters": {
    "countyName": "区县名（**其他区县整改中，暂时只支持`绵竹市`**）。德阳市、绵竹市、广汉市、什邡市、中江县、罗江区、旌阳区、高新区",
    "infoType": "信息类型。默认值:fdzdnr-“法定主动内容”"
  },
  "path": "/sichuan/deyang/govpublicinfo/:countyName/:infoType?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
