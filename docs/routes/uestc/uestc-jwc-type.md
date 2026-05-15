# 电子科技大学 - 教务处

## Coverage
`index-only`

## Route
- Namespace: `uestc`
- Namespace Name: `电子科技大学`
- Route Path: `/uestc/jwc/:type?`
- Route Name: `教务处`
- Example: `/uestc/jwc/student`
- URL: `www.jwc.uestc.edu.cn/`
- Language: `_None_`
- Categories: `university`
- Maintainers: `achjqz, mobyw`
- Source Location: `jwc.ts`
- Source Module: `_None_`

## Description
| 重要公告  | 学生事务公告 | 教师事务公告 | 教学新闻 | 办公室 |
| --------- | ------------ | ------------ | -------- | ------ |
| important | student      | teacher      | teaching | office |

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
  - `www.jwc.uestc.edu.cn/`
- `target`: `/jwc`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 重要公告  | 学生事务公告 | 教师事务公告 | 教学新闻 | 办公室 |\n| --------- | ------------ | ------------ | -------- | ------ |\n| important | student      | teacher      | teaching | office |",
  "example": "/uestc/jwc/student",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 12,
  "location": "jwc.ts",
  "maintainers": [
    "achjqz",
    "mobyw"
  ],
  "name": "教务处",
  "parameters": {
    "type": "默认为 `important`"
  },
  "path": "/jwc/:type?",
  "radar": [
    {
      "source": [
        "www.jwc.uestc.edu.cn/"
      ],
      "target": "/jwc"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "电子科技大学教务处通知（学生事务公告） - Powered by RSSHub",
      "errorAt": "2026-05-13T12:12:37.981Z",
      "errorMessage": "[GET] \"https://www.jwc.uestc.edu.cn/list/256/?page=1\": 403 Forbidden\n",
      "id": "113187940233421824",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.jwc.uestc.edu.cn/",
      "title": "教务处通知（学生事务公告）",
      "type": "feed",
      "url": "rsshub://uestc/jwc/student"
    },
    {
      "description": "电子科技大学教务处通知（重要公告） - Powered by RSSHub",
      "errorAt": "2026-05-13T15:47:02.108Z",
      "errorMessage": "[GET] \"https://www.jwc.uestc.edu.cn/hard/?page=1\": 403 Forbidden\n",
      "id": "113188362354655232",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.jwc.uestc.edu.cn/",
      "title": "教务处通知（重要公告）",
      "type": "feed",
      "url": "rsshub://uestc/jwc/important"
    }
  ],
  "url": "www.jwc.uestc.edu.cn/"
}
```
