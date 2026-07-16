# 起点 - 限时免费

## Coverage
`index-only`

## Route
- Namespace: `qidian`
- Namespace Name: `起点`
- Route Path: `/qidian/free/:type?`
- Route Name: `限时免费`
- Example: `/qidian/free`
- URL: `www.qidian.com/free`
- Language: `_None_`
- Categories: `reading`
- Maintainers: `LogicJake, pseudoyu`
- Source Location: `free.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `type`: 默认不填为起点中文网，填 mm 为起点女生网


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.qidian.com/free`
- `target`: `/free`

## Raw JSON
```json
{
  "categories": [
    "reading"
  ],
  "example": "/qidian/free",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 7,
  "location": "free.ts",
  "maintainers": [
    "LogicJake",
    "pseudoyu"
  ],
  "name": "限时免费",
  "parameters": {
    "type": "默认不填为起点中文网，填 mm 为起点女生网"
  },
  "path": "/free/:type?",
  "radar": [
    {
      "source": [
        "www.qidian.com/free"
      ],
      "target": "/free"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "限时免费-起点中文网 - Powered by RSSHub",
      "errorAt": "2026-07-15T04:50:18.680Z",
      "errorMessage": "Failed to fetch\n",
      "id": "202693934180520960",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.qidian.com/free",
      "title": "起点中文网",
      "type": "feed",
      "url": "rsshub://qidian/free"
    }
  ],
  "url": "www.qidian.com/free"
}
```
