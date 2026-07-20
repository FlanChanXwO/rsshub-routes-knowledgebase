# 豆瓣 - 豆瓣读书论坛

## Coverage
`index-only`

## Route
- Namespace: `douban`
- Namespace Name: `豆瓣`
- Route Path: `/douban/:id/discussion`
- Route Name: `豆瓣读书论坛`
- Example: `/douban/36328704/discussion`
- URL: `www.douban.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `nightmare-mio`
- Source Location: `other/discussion.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 书本id;默认论坛文章使用"按回应时间排序",仅第一页文章


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
  - `book.douban.com/:id/discussion`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/douban/36328704/discussion",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 5,
  "location": "other/discussion.ts",
  "maintainers": [
    "nightmare-mio"
  ],
  "name": "豆瓣读书论坛",
  "parameters": {
    "id": "书本id;默认论坛文章使用\"按回应时间排序\",仅第一页文章"
  },
  "path": "/:id/discussion",
  "radar": [
    {
      "source": [
        "book.douban.com/:id/discussion"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "Error: STACK_TRACE_ERROR\n    at task (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1784:27)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1817:16)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1563:28)\n    at chain (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:599:14)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:98:12\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:40\n    at runWithSuite (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:2258:8)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:10)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1893:54)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)"
  },
  "topFeeds": [
    {
      "description": "太白金星有点烦的论坛 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "73622068229947392",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://book.douban.com/subject/36328704/discussion",
      "title": "太白金星有点烦的论坛",
      "type": "feed",
      "url": "rsshub://douban/36328704/discussion"
    }
  ]
}
```
