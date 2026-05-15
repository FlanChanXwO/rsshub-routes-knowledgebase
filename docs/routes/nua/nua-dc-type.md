# Nanjing University of the Arts 南京艺术学院 - School of Design

## Coverage
`index-only`

## Route
- Namespace: `nua`
- Namespace Name: `Nanjing University of the Arts 南京艺术学院`
- Route Path: `/nua/dc/:type`
- Route Name: `School of Design`
- Example: `/nua/dc/news`
- URL: `index.nua.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `evnydd0sf`
- Source Location: `dc.ts`
- Source Module: `_None_`

## Description
| News Type                | Parameters |
| ------------------------ | ---------- |
| 学院新闻 NEWS            | news       |
| 展览 EXHIBITION          | exhibition |
| 研创 RESEARCH & CREATION | rc         |
| 项目 PROJECT             | project    |
| 党团 PARTY               | party      |
| 后浪 YOUTH               | youth      |

## Parameters
- `type`: News Type


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
  - `dc.nua.edu.cn/:type/list.htm`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| News Type                | Parameters |\n| ------------------------ | ---------- |\n| 学院新闻 NEWS            | news       |\n| 展览 EXHIBITION          | exhibition |\n| 研创 RESEARCH & CREATION | rc         |\n| 项目 PROJECT             | project    |\n| 党团 PARTY               | party      |\n| 后浪 YOUTH               | youth      |",
  "example": "/nua/dc/news",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "dc.ts",
  "maintainers": [
    "evnydd0sf"
  ],
  "name": "School of Design",
  "parameters": {
    "type": "News Type"
  },
  "path": "/dc/:type",
  "radar": [
    {
      "source": [
        "dc.nua.edu.cn/:type/list.htm"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected NaN to be greater than -432000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:37:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:63:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:82:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
