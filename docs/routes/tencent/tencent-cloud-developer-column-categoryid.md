# 腾讯 - 腾讯云开发者社区专栏

## Coverage
`index-only`

## Route
- Namespace: `tencent`
- Namespace Name: `腾讯`
- Route Path: `/tencent/cloud/developer/column/:categoryId?`
- Route Name: `腾讯云开发者社区专栏`
- Example: `/tencent/cloud/developer/column/1`
- URL: `tencent.com`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `lyling`
- Source Location: `cloud/developer/column.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `categoryId`: categoryId from page url


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `cloud.tencent.com/developer/column`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/tencent/cloud/developer/column/1",
  "heat": 139,
  "location": "cloud/developer/column.ts",
  "maintainers": [
    "lyling"
  ],
  "name": "腾讯云开发者社区专栏",
  "parameters": {
    "categoryId": "categoryId from page url"
  },
  "path": "/cloud/developer/column/:categoryId?",
  "radar": [
    {
      "source": [
        "cloud.tencent.com/developer/column"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "- 腾讯云开发者社区 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "56601732214516736",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://docs.rsshub.app/",
      "title": "RSSHub",
      "type": "feed",
      "url": "rsshub://tencent/cloud/developer/column"
    },
    {
      "description": "后端 - 腾讯云开发者社区 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "57690304909571072",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://docs.rsshub.app/",
      "title": "后端",
      "type": "feed",
      "url": "rsshub://tencent/cloud/developer/column/4"
    }
  ]
}
```
