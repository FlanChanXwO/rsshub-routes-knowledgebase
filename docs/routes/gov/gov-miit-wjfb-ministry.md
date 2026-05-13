# 中国人民银行 - 文件发布

## Coverage
`index-only`

## Route
- Namespace: `gov`
- Namespace Name: `中国人民银行`
- Route Path: `/gov/miit/wjfb/:ministry`
- Route Name: `文件发布`
- Example: `/gov/miit/wjfb/ghs`
- URL: `pbc.gov.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `Fatpandac`
- Source Location: `miit/wjfb.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `ministry`: 部门缩写，可以在对应 URL 中获取


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
  - `miit.gov.cn/jgsj/:ministry/wjfb/index.html`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "example": "/gov/miit/wjfb/ghs",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 2,
  "location": "miit/wjfb.ts",
  "maintainers": [
    "Fatpandac"
  ],
  "name": "文件发布",
  "parameters": {
    "ministry": "部门缩写，可以在对应 URL 中获取"
  },
  "path": "/miit/wjfb/:ministry",
  "radar": [
    {
      "source": [
        "miit.gov.cn/jgsj/:ministry/wjfb/index.html"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": null,
      "errorAt": "2025-08-12T08:08:35.112Z",
      "errorMessage": "Cannot read properties of undefined (reading 'set-cookie')\n",
      "id": "177905314710033408",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://gov/miit/wjfb/ghs"
    }
  ]
}
```
