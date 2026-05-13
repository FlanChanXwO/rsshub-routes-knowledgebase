# 国家能源局 - 深圳市住房和建设局

## Coverage
`index-only`

## Route
- Namespace: `gov`
- Namespace Name: `国家能源局`
- Route Path: `/gov/shenzhen/zjj/xxgk/:caty`
- Route Name: `深圳市住房和建设局`
- Example: `/gov/shenzhen/zjj/xxgk/tzgg`
- URL: `www.nea.gov.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `lonn`
- Source Location: `shenzhen/zjj/index.ts`
- Source Module: `_None_`

## Description
| 通知公告 |
| :------: |
|   tzgg   |

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
### Rule 1
- `source`:
  - `zjj.sz.gov.cn/xxgk/:caty`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "| 通知公告 |\n| :------: |\n|   tzgg   |",
  "example": "/gov/shenzhen/zjj/xxgk/tzgg",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 12,
  "location": "shenzhen/zjj/index.ts",
  "maintainers": [
    "lonn"
  ],
  "name": "深圳市住房和建设局",
  "parameters": {
    "caty": "信息类别"
  },
  "path": "/shenzhen/zjj/xxgk/:caty",
  "radar": [
    {
      "source": [
        "zjj.sz.gov.cn/xxgk/:caty"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "深圳市住房和建设局 - 通知公告 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "69966067980854272",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://zjj.sz.gov.cn/xxgk/tzgg/",
      "title": "深圳市住房和建设局 - 通知公告",
      "type": "feed",
      "url": "rsshub://gov/shenzhen/zjj/xxgk/tzgg"
    }
  ]
}
```
