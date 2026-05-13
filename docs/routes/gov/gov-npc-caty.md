# 上海市人民政府 - 通用

## Coverage
`index-only`

## Route
- Namespace: `gov`
- Namespace Name: `上海市人民政府`
- Route Path: `/gov/npc/:caty`
- Route Name: `通用`
- Example: `/gov/npc/c183`
- URL: `sh.gov.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `233yeee`
- Source Location: `npc/index.ts`
- Source Module: `_None_`

## Description
| 立法 | 监督 | 代表 | 理论 | 权威发布 | 滚动新闻 |
| ---- | ---- | ---- | ---- | -------- | -------- |
| c183 | c184 | c185 | c189 | c12435   | c10134   |

## Parameters
- `caty`: 分类名，支持形如 `http://www.npc.gov.cn/npc/c2/*/` 的网站，传入 npc 之后的参数


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
  - `npc.gov.cn/npc/c2/:caty`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "| 立法 | 监督 | 代表 | 理论 | 权威发布 | 滚动新闻 |\n| ---- | ---- | ---- | ---- | -------- | -------- |\n| c183 | c184 | c185 | c189 | c12435   | c10134   |",
  "example": "/gov/npc/c183",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1112,
  "location": "npc/index.ts",
  "maintainers": [
    "233yeee"
  ],
  "name": "通用",
  "parameters": {
    "caty": "分类名，支持形如 `http://www.npc.gov.cn/npc/c2/*/` 的网站，传入 npc 之后的参数"
  },
  "path": "/npc/:caty",
  "radar": [
    {
      "source": [
        "npc.gov.cn/npc/c2/:caty"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "权威发布_中国人大网 - Powered by RSSHub",
      "errorAt": "2026-03-13T13:27:53.178Z",
      "errorMessage": "Cannot read properties of null (reading '1')\n",
      "id": "76238928708564992",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://www.npc.gov.cn/npc/c2/c12435/",
      "title": "权威发布_中国人大网",
      "type": "feed",
      "url": "rsshub://gov/npc/c12435"
    },
    {
      "description": "立法_中国人大网 - Powered by RSSHub",
      "errorAt": "2026-05-11T09:04:51.612Z",
      "errorMessage": "Cannot read properties of null (reading '1')\n",
      "id": "62717033472135175",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://www.npc.gov.cn/npc/c2/c183/",
      "title": "立法_中国人大网",
      "type": "feed",
      "url": "rsshub://gov/npc/c183"
    }
  ]
}
```
