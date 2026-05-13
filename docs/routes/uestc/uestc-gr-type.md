# 电子科技大学 - 研究生院

## Coverage
`index-only`

## Route
- Namespace: `uestc`
- Namespace Name: `电子科技大学`
- Route Path: `/uestc/gr/:type?`
- Route Name: `研究生院`
- Example: `/uestc/gr/student`
- URL: `gr.uestc.edu.cn/`
- Language: `_None_`
- Categories: `university`
- Maintainers: `huyyi, mobyw`
- Source Location: `gr.ts`
- Source Module: `_None_`

## Description
| 重要公告  | 教学管理 | 学位管理 | 学生管理 | 就业实践 |
| --------- | -------- | -------- | -------- | -------- |
| important | teaching | degree   | student  | practice |

## Parameters
- `type`: 默认为 `important`


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `gr.uestc.edu.cn/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 重要公告  | 教学管理 | 学位管理 | 学生管理 | 就业实践 |\n| --------- | -------- | -------- | -------- | -------- |\n| important | teaching | degree   | student  | practice |",
  "example": "/uestc/gr/student",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 6,
  "location": "gr.ts",
  "maintainers": [
    "huyyi",
    "mobyw"
  ],
  "name": "研究生院",
  "parameters": {
    "type": "默认为 `important`"
  },
  "path": "/gr/:type?",
  "radar": [
    {
      "source": [
        "gr.uestc.edu.cn/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "电子科技大学研究生院通知（学生管理） - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "68471708052412416",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://gr.uestc.edu.cn/",
      "title": "研究生院通知（学生管理）",
      "type": "feed",
      "url": "rsshub://uestc/gr/student"
    }
  ],
  "url": "gr.uestc.edu.cn/"
}
```
