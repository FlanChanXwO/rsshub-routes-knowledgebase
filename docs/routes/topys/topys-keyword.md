# TOPYS - 关键字

## Coverage
`index-only`

## Route
- Namespace: `topys`
- Namespace Name: `TOPYS`
- Route Path: `/topys/:keyword?`
- Route Name: `关键字`
- Example: `/topys`
- URL: `topys.cn`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| 创意 | 设计 | 商业 | 艺术 | 文化 | 科技 |
| ---- | ---- | ---- | ---- | ---- | ---- |

## Parameters
- `keyword`: 关键字，可在对应结果页的 URL 中找到


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
  - `topys.cn/search/:keyword`
  - `topys.cn/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 创意 | 设计 | 商业 | 艺术 | 文化 | 科技 |\n| ---- | ---- | ---- | ---- | ---- | ---- |",
  "example": "/topys",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 332,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "关键字",
  "parameters": {
    "keyword": "关键字，可在对应结果页的 URL 中找到"
  },
  "path": "/:keyword?",
  "radar": [
    {
      "source": [
        "topys.cn/search/:keyword",
        "topys.cn/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "Error: STACK_TRACE_ERROR\n    at task (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1784:27)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1817:16)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1563:28)\n    at chain (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:599:14)\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:74:12\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:40\n    at runWithSuite (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:2258:8)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:10)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1893:54)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)"
  },
  "topFeeds": [
    {
      "description": "TOPYS - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "55870828931624960",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.topys.cn/pick",
      "title": "TOPYS",
      "type": "feed",
      "url": "rsshub://topys"
    },
    {
      "description": "设计 - TOPYS - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41489882518602753",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.topys.cn/search/%E8%AE%BE%E8%AE%A1",
      "title": "设计 - TOPYS",
      "type": "feed",
      "url": "rsshub://topys/%E8%AE%BE%E8%AE%A1"
    }
  ]
}
```
