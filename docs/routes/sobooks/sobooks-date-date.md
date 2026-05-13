# SoBooks - 归档

## Coverage
`index-only`

## Route
- Namespace: `sobooks`
- Namespace Name: `SoBooks`
- Route Path: `/sobooks/date/:date?`
- Route Name: `归档`
- Example: `/sobooks/date/2020-11`
- URL: `sobooks.net`
- Language: `_None_`
- Categories: `reading`
- Maintainers: `nczitzk`
- Source Location: `date.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `date`: 日期，见例子，默认为当前年月


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
  - `sobooks.net/:category`
- `target`: `/:category`

## Raw JSON
```json
{
  "categories": [
    "reading"
  ],
  "example": "/sobooks/date/2020-11",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "date.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "归档",
  "parameters": {
    "date": "日期，见例子，默认为当前年月"
  },
  "path": "/date/:date?",
  "radar": [
    {
      "source": [
        "sobooks.net/:category"
      ],
      "target": "/:category"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
