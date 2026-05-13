# 中国人民银行 - 贵州省教育厅 - 通知公告

## Coverage
`index-only`

## Route
- Namespace: `gov`
- Namespace Name: `中国人民银行`
- Route Path: `/gov/guizhou/jyt/tzgg`
- Route Name: `贵州省教育厅 - 通知公告`
- Example: `/gov/guizhou/jyt/tzgg`
- URL: `jyt.guizhou.gov.cn/zwgk/tzgg/`
- Language: `_None_`
- Categories: `government`
- Maintainers: `sheetung`
- Source Location: `guizhou/jyt.ts`
- Source Module: `_None_`

## Description
贵州省教育厅官方网站通知公告 RSS 源

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
  - `jyt.guizhou.gov.cn/zwgk/tzgg/`
  - `jyt.guizhou.gov.cn/zwgk/tzgg/index.html`
- `target`: `/guizhou/jyt/tzgg`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "贵州省教育厅官方网站通知公告 RSS 源",
  "example": "/gov/guizhou/jyt/tzgg",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "guizhou/jyt.ts",
  "maintainers": [
    "sheetung"
  ],
  "name": "贵州省教育厅 - 通知公告",
  "parameters": {},
  "path": "/guizhou/jyt/tzgg",
  "radar": [
    {
      "source": [
        "jyt.guizhou.gov.cn/zwgk/tzgg/",
        "jyt.guizhou.gov.cn/zwgk/tzgg/index.html"
      ],
      "target": "/guizhou/jyt/tzgg"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at runNextTicks (node:internal/process/task_queues:69:3)\n    at listOnTimeout (node:internal/timers:567:9)\n    at processTimers (node:internal/timers:541:7)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "贵州省教育厅门户网站通知公告 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "238150952866085888",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://jyt.guizhou.gov.cn/zwgk/tzgg/",
      "title": "贵州省教育厅 - 通知公告",
      "type": "feed",
      "url": "rsshub://gov/guizhou/jyt/tzgg"
    }
  ],
  "url": "jyt.guizhou.gov.cn/zwgk/tzgg/"
}
```
