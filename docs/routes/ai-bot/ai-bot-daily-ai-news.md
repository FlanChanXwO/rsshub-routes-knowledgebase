# AI工具集 - 每日AI资讯

## Coverage
`index-only`

## Route
- Namespace: `ai-bot`
- Namespace Name: `AI工具集`
- Route Path: `/ai-bot/daily-ai-news`
- Route Name: `每日AI资讯`
- Example: `/ai-bot/daily-ai-news`
- URL: `ai-bot.cn/daily-ai-news`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `redwood9`
- Source Location: `daily-ai-news.ts`
- Source Module: `_None_`

## Description
获取 AI 工具集网站的每日 AI 资讯汇总。

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
  - `ai-bot.cn/daily-ai-news`
  - `ai-bot.cn/daily-ai-news/`
- `target`: `/daily-ai-news`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "获取 AI 工具集网站的每日 AI 资讯汇总。",
  "example": "/ai-bot/daily-ai-news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 28,
  "location": "daily-ai-news.ts",
  "maintainers": [
    "redwood9"
  ],
  "name": "每日AI资讯",
  "parameters": {},
  "path": "/daily-ai-news",
  "radar": [
    {
      "source": [
        "ai-bot.cn/daily-ai-news",
        "ai-bot.cn/daily-ai-news/"
      ],
      "target": "/daily-ai-news"
    }
  ],
  "test": {
    "code": 1,
    "message": "Error: STACK_TRACE_ERROR\n    at task (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1784:27)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1817:16)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1563:28)\n    at chain (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:599:14)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:98:12\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:40\n    at runWithSuite (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:2258:8)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:10)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1893:54)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)"
  },
  "topFeeds": [
    {
      "description": "每日AI资讯 | AI工具集 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "235583235330654208",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://ai-bot.cn/daily-ai-news/",
      "title": "每日AI资讯 | AI工具集",
      "type": "feed",
      "url": "rsshub://ai-bot/daily-ai-news"
    }
  ],
  "url": "ai-bot.cn/daily-ai-news"
}
```
