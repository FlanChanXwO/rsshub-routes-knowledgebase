# 中国科学技术大学 - 电子工程与信息科学系

## Coverage
`index-only`

## Route
- Namespace: `ustc`
- Namespace Name: `中国科学技术大学`
- Route Path: `/ustc/eeis/:type?`
- Route Name: `电子工程与信息科学系`
- Example: `/ustc/eeis/tzgg`
- URL: `eeis.ustc.edu.cn/`
- Language: `_None_`
- Categories: `university`
- Maintainers: `jasongzy`
- Source Location: `eeis.ts`
- Source Module: `_None_`

## Description
| 通知公告 | 新闻信息 |
| -------- | -------- |
| tzgg     | xwxx     |

## Parameters
- `type`: 分类，见下表，默认为通知公告


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
  - `eeis.ustc.edu.cn/`
- `target`: `/eeis`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 通知公告 | 新闻信息 |\n| -------- | -------- |\n| tzgg     | xwxx     |",
  "example": "/ustc/eeis/tzgg",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "eeis.ts",
  "maintainers": [
    "jasongzy"
  ],
  "name": "电子工程与信息科学系",
  "parameters": {
    "type": "分类，见下表，默认为通知公告"
  },
  "path": "/eeis/:type?",
  "radar": [
    {
      "source": [
        "eeis.ustc.edu.cn/"
      ],
      "target": "/eeis"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "eeis.ustc.edu.cn/"
}
```
