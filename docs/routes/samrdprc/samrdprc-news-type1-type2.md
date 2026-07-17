# 国家市场监督管理总局缺陷产品管理中心 - 召回信息

## Coverage
`index-only`

## Route
- Namespace: `samrdprc`
- Namespace Name: `国家市场监督管理总局缺陷产品管理中心`
- Route Path: `/samrdprc/news/:type1/:type2`
- Route Name: `召回信息`
- Example: `/samrdprc/news/xfpzh/xfpgnzh`
- URL: `www.samrdprc.org.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `a180285`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
| 类型中文   | 召回类型 ID1 | 召回类型 ID2 |
| ---------- | ------------ | ------------ |
| 消费品召回 | xfpzh        | xfpgnzh      |
| 汽车召回   | qczh         | gnzhqc       |

## Parameters
- `type1`: 召回类型ID1，见下表
- `type2`: 召回类型ID2，见下表


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
  - `www.samrdprc.org.cn/:type1/:type2`
- `target`: `/news/:type1/:type2`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "| 类型中文   | 召回类型 ID1 | 召回类型 ID2 |\n| ---------- | ------------ | ------------ |\n| 消费品召回 | xfpzh        | xfpgnzh      |\n| 汽车召回   | qczh         | gnzhqc       |",
  "example": "/samrdprc/news/xfpzh/xfpgnzh",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 9,
  "location": "news.ts",
  "maintainers": [
    "a180285"
  ],
  "name": "召回信息",
  "parameters": {
    "type1": "召回类型ID1，见下表",
    "type2": "召回类型ID2，见下表"
  },
  "path": "/news/:type1/:type2",
  "radar": [
    {
      "source": [
        "www.samrdprc.org.cn/:type1/:type2"
      ],
      "target": "/news/:type1/:type2"
    }
  ],
  "test": {
    "code": 1,
    "message": "Error: STACK_TRACE_ERROR\n    at task (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1784:27)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1817:16)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1563:28)\n    at chain (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:599:14)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:98:12\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:40\n    at runWithSuite (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:2258:8)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:10)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1893:54)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)"
  },
  "topFeeds": [
    {
      "description": "国内消费品召回新闻 - 国家市场监督管理总局 - Powered by RSSHub",
      "errorAt": "2026-07-15T04:45:22.993Z",
      "errorMessage": "Failed to fetch\n",
      "id": "160626513899715584",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.samrdprc.org.cn/xfpzh/xfpgnzh",
      "title": "国内消费品召回新闻 - 国家市场监督管理总局",
      "type": "feed",
      "url": "rsshub://samrdprc/news/xfpzh/xfpgnzh"
    }
  ]
}
```
