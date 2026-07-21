# 实用日本语鉴定考试（J.TEST） - 公告

## Coverage
`index-only`

## Route
- Namespace: `j-test`
- Namespace Name: `实用日本语鉴定考试（J.TEST）`
- Route Path: `/j-test/news`
- Route Name: `公告`
- Example: `/j-test/news`
- URL: `www.j-test.com`
- Language: `_None_`
- Categories: `study`
- Maintainers: `kuhahku`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


## Features
- `supportRadar`: true

## Radar
### Rule 1
- `source`:
  - `www.j-test.com`
- `target`: `/news`

## Raw JSON
```json
{
  "categories": [
    "study"
  ],
  "description": "",
  "example": "/j-test/news",
  "features": {
    "supportRadar": true
  },
  "heat": 0,
  "location": "news.ts",
  "maintainers": [
    "kuhahku"
  ],
  "name": "公告",
  "parameters": {},
  "path": "/news",
  "radar": [
    {
      "source": [
        "www.j-test.com"
      ],
      "target": "/news"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "www.j-test.com"
}
```
