# 新片场 - 排行榜

## Coverage
`index-only`

## Route
- Namespace: `xinpianchang`
- Namespace Name: `新片场`
- Route Path: `/xinpianchang/rank/:category?`
- Route Name: `排行榜`
- Example: `/xinpianchang/rank`
- URL: `xinpianchang.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `rank.ts`
- Source Module: `_None_`

## Description
| 分类     | id         |
| -------- | ---------- |
| 总榜     | all        |
| 精选榜   | staffPicks |
| 广告     | ad         |
| 宣传片   | publicity  |
| 创意     | creative   |
| 干货教程 | backstage  |

## Parameters
- `category`: 分类 id，可在对应排行榜页 URL 中找到，见下表，默认为 `all` ，即总榜


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 分类     | id         |\n| -------- | ---------- |\n| 总榜     | all        |\n| 精选榜   | staffPicks |\n| 广告     | ad         |\n| 宣传片   | publicity  |\n| 创意     | creative   |\n| 干货教程 | backstage  |",
  "example": "/xinpianchang/rank",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "rank.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "排行榜",
  "parameters": {
    "category": "分类 id，可在对应排行榜页 URL 中找到，见下表，默认为 `all` ，即总榜"
  },
  "path": "/rank/:category?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
