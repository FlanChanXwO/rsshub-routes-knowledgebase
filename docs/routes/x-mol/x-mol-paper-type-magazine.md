# X-MOL - Journal

## Coverage
`index-only`

## Route
- Namespace: `x-mol`
- Namespace Name: `X-MOL`
- Route Path: `/x-mol/paper/:type/:magazine`
- Route Name: `Journal`
- Example: `/x-mol/paper/0/9`
- URL: `x-mol.com`
- Language: `_None_`
- Categories: `journal`
- Maintainers: `cssxsh`
- Source Location: `paper.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `type`: type
- `magazine`: magazine


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "example": "/x-mol/paper/0/9",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 3,
  "location": "paper.ts",
  "maintainers": [
    "cssxsh"
  ],
  "name": "Journal",
  "parameters": {
    "magazine": "magazine",
    "type": "type"
  },
  "path": "/paper/:type/:magazine",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Accounts of Chemical Research期刊最新论文，,Top期刊最新论文图文内容，出版社网站每日同步更新，点击标题直达论文原文，自定义关注的期刊，覆盖PubMed的论文库，快速方便精准的找到您想要的论文 - Powered by RSSHub",
      "errorAt": "2025-12-30T06:09:51.716Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "198071936883287040",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://docs.rsshub.app/",
      "title": "Accounts of Chemical Research期刊新发论文, 化学/材料, - X-MOL",
      "type": "feed",
      "url": "rsshub://x-mol/paper/0/9"
    }
  ]
}
```
