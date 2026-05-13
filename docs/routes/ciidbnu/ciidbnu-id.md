# 中国收入分配研究院 - 分类

## Coverage
`index-only`

## Route
- Namespace: `ciidbnu`
- Namespace Name: `中国收入分配研究院`
- Route Path: `/ciidbnu/:id?`
- Route Name: `分类`
- Example: `/ciidbnu`
- URL: `ciidbnu.org`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| 社会动态 | 院内新闻 | 学术观点 | 文献书籍 | 工作论文 | 专题讨论 |
| -------- | -------- | -------- | -------- | -------- | -------- |
| 1        | 5        | 3        | 4        | 6        | 8        |

## Parameters
- `id`: 分类 id，可在分类页地址栏 URL 中找到


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
  "description": "| 社会动态 | 院内新闻 | 学术观点 | 文献书籍 | 工作论文 | 专题讨论 |\n| -------- | -------- | -------- | -------- | -------- | -------- |\n| 1        | 5        | 3        | 4        | 6        | 8        |",
  "example": "/ciidbnu",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "分类",
  "parameters": {
    "id": "分类 id，可在分类页地址栏 URL 中找到"
  },
  "path": "/:id?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
