# 上海市人民政府 - 获取国家医师资格考试通知

## Coverage
`index-only`

## Route
- Namespace: `gov`
- Namespace Name: `上海市人民政府`
- Route Path: `/gov/jinan/healthcommission/medical_exam_notice`
- Route Name: `获取国家医师资格考试通知`
- Example: `/gov/jinan/healthcommission/medical_exam_notice`
- URL: `jnmhc.jinan.gov.cn/*`
- Language: `_None_`
- Categories: `government`
- Maintainers: `tzjyxb`
- Source Location: `jinan/healthcommission/medical-exam-notice.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


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
  - `jnmhc.jinan.gov.cn/*`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "example": "/gov/jinan/healthcommission/medical_exam_notice",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "jinan/healthcommission/medical-exam-notice.ts",
  "maintainers": [
    "tzjyxb"
  ],
  "name": "获取国家医师资格考试通知",
  "parameters": {},
  "path": "/jinan/healthcommission/medical_exam_notice",
  "radar": [
    {
      "source": [
        "jnmhc.jinan.gov.cn/*"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "jnmhc.jinan.gov.cn/*"
}
```
