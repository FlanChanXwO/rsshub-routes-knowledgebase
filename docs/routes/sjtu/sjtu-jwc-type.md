# 上海交通大学 - 教务处通知公告

## Coverage
`index-only`

## Route
- Namespace: `sjtu`
- Namespace Name: `上海交通大学`
- Route Path: `/sjtu/jwc/:type?`
- Route Name: `教务处通知公告`
- Example: `/sjtu/jwc`
- URL: `www.sjtu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `SeanChao`
- Source Location: `jwc.ts`
- Source Module: `_None_`

## Description
\| 新闻中心 | 通知通告 | 教学运行  | 注册学务 | 研究办 | 教改办 | 综合办 | 语言文字 | 工会与支部 | 通识教育 | 面向学生的通知 |
\| -------- | -------- | --------- | -------- | ------ | ------ | ------ | -------- | ---------- | -------- |
\| news     | notice   | operation | affairs  | yjb    | jgb    | zhb    | language | party      | ge       | students  |

## Parameters
- `type`: 默认为 notice


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
  "description": "\\| 新闻中心 | 通知通告 | 教学运行  | 注册学务 | 研究办 | 教改办 | 综合办 | 语言文字 | 工会与支部 | 通识教育 | 面向学生的通知 |\n\\| -------- | -------- | --------- | -------- | ------ | ------ | ------ | -------- | ---------- | -------- |\n\\| news     | notice   | operation | affairs  | yjb    | jgb    | zhb    | language | party      | ge       | students  |",
  "example": "/sjtu/jwc",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 17,
  "location": "jwc.ts",
  "maintainers": [
    "SeanChao"
  ],
  "name": "教务处通知公告",
  "parameters": {
    "type": "默认为 notice"
  },
  "path": "/jwc/:type?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "上海交通大学教务处 通知通告 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "66699654854455296",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://jwc.sjtu.edu.cn/xwtg/tztg.htm",
      "title": "上海交通大学教务处 通知通告",
      "type": "feed",
      "url": "rsshub://sjtu/jwc"
    }
  ]
}
```
