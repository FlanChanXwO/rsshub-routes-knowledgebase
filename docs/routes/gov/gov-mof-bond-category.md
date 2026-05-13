# 中国人民银行 - 专题

## Coverage
`index-only`

## Route
- Namespace: `gov`
- Namespace Name: `中国人民银行`
- Route Path: `/gov/mof/bond/:category?`
- Route Name: `专题`
- Example: `/gov/mof/bond`
- URL: `pbc.gov.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `la3rence`
- Source Location: `mof/bond.ts`
- Source Module: `_None_`

## Description
#### 政府债券管理

| 国债管理工作动态 | 记账式国债 (含特别国债) 发行 | 储蓄国债发行 | 地方政府债券管理      |
| ---------------- | ---------------------------- | ------------ | --------------------- |
| gzfxgzdt         | gzfxzjs                      | gzfxdzs      | difangzhengfuzhaiquan |

## Parameters
- `category`: 专题，见下表，默认为国债管理工作动态


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
    "government"
  ],
  "description": "#### 政府债券管理\n\n| 国债管理工作动态 | 记账式国债 (含特别国债) 发行 | 储蓄国债发行 | 地方政府债券管理      |\n| ---------------- | ---------------------------- | ------------ | --------------------- |\n| gzfxgzdt         | gzfxzjs                      | gzfxdzs      | difangzhengfuzhaiquan |",
  "example": "/gov/mof/bond",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 55,
  "location": "mof/bond.ts",
  "maintainers": [
    "la3rence"
  ],
  "name": "专题",
  "parameters": {
    "category": "专题，见下表，默认为国债管理工作动态"
  },
  "path": "/mof/bond/:category?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "国债管理工作动态 - 中华人民共和国财政部 - Powered by RSSHub",
      "errorAt": "2026-02-12T02:46:43.224Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "72200004362793984",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://gks.mof.gov.cn/ztztz/guozaiguanli/gzfxgzdt/",
      "title": "国债管理工作动态",
      "type": "feed",
      "url": "rsshub://gov/mof/bond"
    },
    {
      "description": "储蓄国债发行 - 中华人民共和国财政部 - Powered by RSSHub",
      "errorAt": "2026-02-12T06:18:06.323Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "100135024449222656",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://gks.mof.gov.cn/ztztz/guozaiguanli/gzfxdzs/",
      "title": "储蓄国债发行",
      "type": "feed",
      "url": "rsshub://gov/mof/bond/gzfxdzs"
    }
  ]
}
```
