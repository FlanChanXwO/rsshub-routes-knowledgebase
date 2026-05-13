# 山东大学 - 教务处

## Coverage
`index-only`

## Route
- Namespace: `sdu`
- Namespace Name: `山东大学`
- Route Path: `/sdu/wh/jwc/:column?`
- Route Name: `教务处`
- Example: `/sdu/wh/jwc/gztz`
- URL: `www.sdu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `kxxt`
- Source Location: `wh/jwc.ts`
- Source Module: `_None_`

## Description
| 规章制度 | 专业建设 | 实践教学 | 支部风采 | 服务指南 | 教务要闻 | 工作通知 | 教务简报 | 常用下载 |
| -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| gzzd     | zyjs     | sjjx     | zbfc     | fwzn     | jwyw     | gztz     | jwjb     | cyxz     |

## Parameters
- `column`: 专栏名称，默认为工作通知（`gztz`）


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
    "university"
  ],
  "description": "| 规章制度 | 专业建设 | 实践教学 | 支部风采 | 服务指南 | 教务要闻 | 工作通知 | 教务简报 | 常用下载 |\n| -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- | -------- |\n| gzzd     | zyjs     | sjjx     | zbfc     | fwzn     | jwyw     | gztz     | jwjb     | cyxz     |",
  "example": "/sdu/wh/jwc/gztz",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "wh/jwc.ts",
  "maintainers": [
    "kxxt"
  ],
  "name": "教务处",
  "parameters": {
    "column": "专栏名称，默认为工作通知（`gztz`）"
  },
  "path": "/wh/jwc/:column?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
