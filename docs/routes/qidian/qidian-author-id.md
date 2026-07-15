# 起点 - 作者

## Coverage
`index-only`

## Route
- Namespace: `qidian`
- Namespace Name: `起点`
- Route Path: `/qidian/author/:id`
- Route Name: `作者`
- Example: `/qidian/author/9639927`
- URL: `qidian.com`
- Language: `_None_`
- Categories: `reading`
- Maintainers: `miles170, pseudoyu`
- Source Location: `author.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 作者 id, 可在作者页面 URL 找到


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
  - `my.qidian.com/author/:id`

## Raw JSON
```json
{
  "categories": [
    "reading"
  ],
  "example": "/qidian/author/9639927",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "author.tsx",
  "maintainers": [
    "miles170",
    "pseudoyu"
  ],
  "name": "作者",
  "parameters": {
    "id": "作者 id, 可在作者页面 URL 找到"
  },
  "path": "/author/:id",
  "radar": [
    {
      "source": [
        "my.qidian.com/author/:id"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
