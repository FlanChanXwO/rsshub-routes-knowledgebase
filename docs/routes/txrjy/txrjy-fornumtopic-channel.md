# 通信人家园 - 论坛 频道

## Coverage
`index-only`

## Route
- Namespace: `txrjy`
- Namespace Name: `通信人家园`
- Route Path: `/txrjy/fornumtopic/:channel?`
- Route Name: `论坛 频道`
- Example: `/txrjy/fornumtopic`
- URL: `txrjy.com`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `Fatpandac`
- Source Location: `fornumtopic.tsx`
- Source Module: `_None_`

## Description
| 最新 500 个主题帖 | 最新 500 个回复帖 | 最新精华帖 | 最新精华帖 | 一周热帖 | 本月热帖 |
| :---------------: | :---------------: | :--------: | :--------: | :------: | :------: |
|         1         |         2         |      3     |      4     |     5    |     6    |

## Parameters
- `channel`: 频道的 id，见下表，默认为最新500个主题帖


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
    "bbs"
  ],
  "description": "| 最新 500 个主题帖 | 最新 500 个回复帖 | 最新精华帖 | 最新精华帖 | 一周热帖 | 本月热帖 |\n| :---------------: | :---------------: | :--------: | :--------: | :------: | :------: |\n|         1         |         2         |      3     |      4     |     5    |     6    |",
  "example": "/txrjy/fornumtopic",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 122,
  "location": "fornumtopic.tsx",
  "maintainers": [
    "Fatpandac"
  ],
  "name": "论坛 频道",
  "parameters": {
    "channel": "频道的 id，见下表，默认为最新500个主题帖"
  },
  "path": "/fornumtopic/:channel?",
  "test": {
    "code": 1,
    "message": "Error: STACK_TRACE_ERROR\n    at task (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1784:27)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1817:16)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1563:28)\n    at chain (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:599:14)\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:74:12\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:40\n    at runWithSuite (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:2258:8)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:10)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1893:54)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)"
  },
  "topFeeds": [
    {
      "description": "通信人家园 - 论坛 一周热帖 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "67830551877448704",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.txrjy.com/c114-listnewtopic.php?typeid=5",
      "title": "通信人家园 - 论坛 一周热帖",
      "type": "feed",
      "url": "rsshub://txrjy/fornumtopic/5"
    },
    {
      "description": "通信人家园 - 论坛 最新500主题帖 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "67830377077194752",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.txrjy.com/c114-listnewtopic.php?typeid=1",
      "title": "通信人家园 - 论坛 最新500主题帖",
      "type": "feed",
      "url": "rsshub://txrjy/fornumtopic/1"
    }
  ]
}
```
