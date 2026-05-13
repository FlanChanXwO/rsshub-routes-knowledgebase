# 上海市人民政府 - 新闻

## Coverage
`index-only`

## Route
- Namespace: `gov`
- Namespace Name: `上海市人民政府`
- Route Path: `/gov/moe/:type`
- Route Name: `新闻`
- Example: `/gov/moe/policy_anal`
- URL: `sh.gov.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `Crawler995`
- Source Location: `moe/moe.ts`
- Source Module: `_None_`

## Description
|   政策解读   |   最新文件   | 公告公示 |      教育部简报     |     教育要闻     |
| :----------: | :----------: | :------: | :-----------------: | :--------------: |
| policy\_anal | newest\_file |  notice  | edu\_ministry\_news | edu\_focus\_news |

## Parameters
- `type`: 分类名


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
  "description": "|   政策解读   |   最新文件   | 公告公示 |      教育部简报     |     教育要闻     |\n| :----------: | :----------: | :------: | :-----------------: | :--------------: |\n| policy\\_anal | newest\\_file |  notice  | edu\\_ministry\\_news | edu\\_focus\\_news |",
  "example": "/gov/moe/policy_anal",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 167,
  "location": "moe/moe.ts",
  "maintainers": [
    "Crawler995"
  ],
  "name": "新闻",
  "parameters": {
    "type": "分类名"
  },
  "path": "/moe/:type",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "政策解读 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "42176727615320071",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.moe.gov.cn/",
      "title": "政策解读",
      "type": "feed",
      "url": "rsshub://gov/moe/policy_anal"
    },
    {
      "description": "公告公示 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "71386837481924626",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.moe.gov.cn/",
      "title": "公告公示",
      "type": "feed",
      "url": "rsshub://gov/moe/notice"
    }
  ]
}
```
