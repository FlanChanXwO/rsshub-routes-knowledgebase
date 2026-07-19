# 爱思想 - 栏目

## Coverage
`index-only`

## Route
- Namespace: `aisixiang`
- Namespace Name: `爱思想`
- Route Path: `/aisixiang/column/:id`
- Route Name: `栏目`
- Example: `/aisixiang/column/722`
- URL: `aisixiang.com`
- Language: `_None_`
- Categories: `reading, popular`
- Maintainers: `HenryQW, nczitzk`
- Source Location: `column.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 栏目 ID, 可在对应栏目 URL 中找到


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
    "reading",
    "popular"
  ],
  "example": "/aisixiang/column/722",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1705,
  "location": "column.ts",
  "maintainers": [
    "HenryQW",
    "nczitzk"
  ],
  "name": "栏目",
  "parameters": {
    "id": "栏目 ID, 可在对应栏目 URL 中找到"
  },
  "path": "/column/:id",
  "test": {
    "code": 1,
    "message": "Error: STACK_TRACE_ERROR\n    at task (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1784:27)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1817:16)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1563:28)\n    at chain (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:599:14)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:98:12\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:40\n    at runWithSuite (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:2258:8)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:10)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1893:54)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)"
  },
  "topFeeds": [
    {
      "description": "爱思想 - [国际关系时评] - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "69571398918375452",
      "image": "https://oss.aisixiang.com/images/logo.jpg",
      "ownerUserId": null,
      "siteUrl": "https://www.aisixiang.com/data/search?column=8",
      "title": "爱思想 - [国际关系时评]",
      "type": "feed",
      "url": "rsshub://aisixiang/column/8"
    },
    {
      "description": "爱思想 - [国际政治经济学] - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "69571398918375456",
      "image": "https://oss.aisixiang.com/images/logo.jpg",
      "ownerUserId": null,
      "siteUrl": "https://www.aisixiang.com/data/search?column=767",
      "title": "爱思想 - [国际政治经济学]",
      "type": "feed",
      "url": "rsshub://aisixiang/column/767"
    }
  ]
}
```
