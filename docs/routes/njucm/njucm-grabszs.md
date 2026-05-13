# 南京中医药大学 - 研究生院博士招生

## Coverage
`index-only`

## Route
- Namespace: `njucm`
- Namespace Name: `南京中医药大学`
- Route Path: `/njucm/grabszs`
- Route Name: `研究生院博士招生`
- Example: `/njucm/grabszs`
- URL: `lib.njucm.edu.cn/2899/list.htm`
- Language: `_None_`
- Categories: `university`
- Maintainers: `real-jiakai`
- Source Location: `grabs.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


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
  - `lib.njucm.edu.cn/2899/list.htm`
  - `lib.njucm.edu.cn/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/njucm/grabszs",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "grabs.ts",
  "maintainers": [
    "real-jiakai"
  ],
  "name": "研究生院博士招生",
  "parameters": {},
  "path": "/grabszs",
  "radar": [
    {
      "source": [
        "lib.njucm.edu.cn/2899/list.htm",
        "lib.njucm.edu.cn/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "lib.njucm.edu.cn/2899/list.htm"
}
```
