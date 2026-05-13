# AInvest - Latest Article

## Coverage
`index-only`

## Route
- Namespace: `ainvest`
- Namespace Name: `AInvest`
- Route Path: `/ainvest/article`
- Route Name: `Latest Article`
- Example: `/ainvest/article`
- URL: `www.ainvest.com/news/articles-latest/`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `TonyRL`
- Source Location: `article.ts`
- Source Module: `_None_`

## Description
_None_

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
  - `www.ainvest.com/news/articles-latest/`
  - `www.ainvest.com`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/ainvest/article",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 13,
  "location": "article.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "Latest Article",
  "parameters": {},
  "path": "/article",
  "radar": [
    {
      "source": [
        "www.ainvest.com/news/articles-latest/",
        "www.ainvest.com"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "Error: STACK_TRACE_ERROR\n    at task (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1784:27)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1817:16)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1563:28)\n    at chain (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:599:14)\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:74:12\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:40\n    at runWithSuite (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:2258:8)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:10)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1893:54)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)"
  },
  "topFeeds": [
    {
      "description": "AInvest - Latest Articles - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "165445337069434882",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.ainvest.com/news/articles-latest/",
      "title": "AInvest - Latest Articles",
      "type": "feed",
      "url": "rsshub://ainvest/article"
    }
  ],
  "url": "www.ainvest.com/news/articles-latest/"
}
```
