# 国家能源局 - 深圳市人民政府

## Coverage
`index-only`

## Route
- Namespace: `gov`
- Namespace Name: `国家能源局`
- Route Path: `/gov/shenzhen/xxgk/zfxxgj/:caty`
- Route Name: `深圳市人民政府`
- Example: `/gov/shenzhen/xxgk/zfxxgj/tzgg`
- URL: `www.nea.gov.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `laoxua`
- Source Location: `shenzhen/xxgk/zfxxgj.ts`
- Source Module: `_None_`

## Description
| 通知公告 | 政府采购 | 资金信息 | 重大项目 |
| :------: | :------: | :------: | :------: |
|   tzgg   |   zfcg   |   zjxx   |   zdxm   |

## Parameters
- `caty`: 信息类别


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
  "description": "| 通知公告 | 政府采购 | 资金信息 | 重大项目 |\n| :------: | :------: | :------: | :------: |\n|   tzgg   |   zfcg   |   zjxx   |   zdxm   |",
  "example": "/gov/shenzhen/xxgk/zfxxgj/tzgg",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "shenzhen/xxgk/zfxxgj.ts",
  "maintainers": [
    "laoxua"
  ],
  "name": "深圳市人民政府",
  "parameters": {
    "caty": "信息类别"
  },
  "path": "/shenzhen/xxgk/zfxxgj/:caty",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
