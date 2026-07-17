# 纷享销客 CRM - 文章

## Coverage
`index-only`

## Route
- Namespace: `fxiaoke`
- Namespace Name: `纷享销客 CRM`
- Route Path: `/fxiaoke/crm/:type`
- Route Name: `文章`
- Example: `/fxiaoke/crm/news`
- URL: `fxiaoke.com`
- Language: `_None_`
- Categories: `blog`
- Maintainers: `akynazh`
- Source Location: `crm.ts`
- Source Module: `_None_`

## Description
| 全部文章 | 文章干货 | CRM 知识 | 纷享动态        | 签约喜报  |
| -------- | -------- | -------- | --------------- | --------- |
| news     | blog     | articles | about-influence | customers |

## Parameters
- `type`: 文章类型, 见下表


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
    "blog"
  ],
  "description": "| 全部文章 | 文章干货 | CRM 知识 | 纷享动态        | 签约喜报  |\n| -------- | -------- | -------- | --------------- | --------- |\n| news     | blog     | articles | about-influence | customers |",
  "example": "/fxiaoke/crm/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 14,
  "location": "crm.ts",
  "maintainers": [
    "akynazh"
  ],
  "name": "文章",
  "parameters": {
    "type": "文章类型, 见下表"
  },
  "path": "/crm/:type",
  "test": {
    "code": 1,
    "message": "Error: STACK_TRACE_ERROR\n    at task (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1784:27)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1817:16)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1563:28)\n    at chain (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:599:14)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:98:12\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:40\n    at runWithSuite (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:2258:8)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:10)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1893:54)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)"
  },
  "topFeeds": [
    {
      "description": "为企业提供CRM系统、数字化转型等方面的专业知识，帮您用好数字化工具开启企业新增长之路。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "73991220743306240",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.fxiaoke.com/crm/news/",
      "title": "全部文章 - 纷享销客 CRM",
      "type": "feed",
      "url": "rsshub://fxiaoke/crm/news"
    },
    {
      "description": "为神州数码、中国常柴、3M、元气森林等超5000家大中型企业提供数字化增长服务。 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "69626378876905472",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.fxiaoke.com/crm/customers/",
      "title": "签约喜报 - 纷享销客 CRM",
      "type": "feed",
      "url": "rsshub://fxiaoke/crm/customers"
    }
  ]
}
```
