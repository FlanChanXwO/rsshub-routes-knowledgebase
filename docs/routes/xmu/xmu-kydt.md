# Xiamen University - 科研动态

## Coverage
`index-only`

## Route
- Namespace: `xmu`
- Namespace Name: `Xiamen University`
- Route Path: `/xmu/kydt`
- Route Name: `科研动态`
- Example: `/xmu/kydt`
- URL: `soe.xmu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `linsenwang`
- Source Location: `kydt.ts`
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
  - `soe.xmu.edu.cn/kxyj/kydt.htm`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/xmu/kydt",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "kydt.ts",
  "maintainers": [
    "linsenwang"
  ],
  "name": "科研动态",
  "path": "/kydt",
  "radar": [
    {
      "source": [
        "soe.xmu.edu.cn/kxyj/kydt.htm"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
