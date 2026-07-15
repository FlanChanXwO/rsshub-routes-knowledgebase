# 编程导航 - 问答

## Coverage
`index-only`

## Route
- Namespace: `codefather`
- Namespace Name: `编程导航`
- Route Path: `/codefather/questions/:sort?`
- Route Name: `问答`
- Example: `/codefather/questions`
- URL: `www.codefather.cn`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `JackyST0`
- Source Location: `questions.ts`
- Source Module: `_None_`

## Description
获取编程导航社区的问答内容，支持按最新、热门排序。

## Parameters
- `sort`: 排序方式，可选 `new`（最新）、`hot`（热门），默认为 `new`


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
  - `www.codefather.cn/qa`
  - `www.codefather.cn`
- `target`: `/questions`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "description": "获取编程导航社区的问答内容，支持按最新、热门排序。",
  "example": "/codefather/questions",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "questions.ts",
  "maintainers": [
    "JackyST0"
  ],
  "name": "问答",
  "parameters": {
    "sort": "排序方式，可选 `new`（最新）、`hot`（热门），默认为 `new`"
  },
  "path": "/questions/:sort?",
  "radar": [
    {
      "source": [
        "www.codefather.cn/qa",
        "www.codefather.cn"
      ],
      "target": "/questions"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
