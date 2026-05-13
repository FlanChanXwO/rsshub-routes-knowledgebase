# 潍坊学院 - 新闻

## Coverage
`index-only`

## Route
- Namespace: `wfu`
- Namespace Name: `潍坊学院`
- Route Path: `/wfu/news/:type?`
- Route Name: `新闻`
- Example: `/wfu/news/wyyw`
- URL: `news.wfu.edu.cn/`
- Language: `_None_`
- Categories: `university`
- Maintainers: `cccht`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
| **内容** | **参数** |
| :------: | :------: |
| 潍院要闻 |   wyyw   |
| 综合新闻 |   zhxw   |
| 学术纵横 |   xszh   |

## Parameters
- `type`: 分类，默认为 `wyyw`，具体参数见下表


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
  - `news.wfu.edu.cn/`
- `target`: `/news`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| **内容** | **参数** |\n| :------: | :------: |\n| 潍院要闻 |   wyyw   |\n| 综合新闻 |   zhxw   |\n| 学术纵横 |   xszh   |",
  "example": "/wfu/news/wyyw",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "news.ts",
  "maintainers": [
    "cccht"
  ],
  "name": "新闻",
  "parameters": {
    "type": "分类，默认为 `wyyw`，具体参数见下表"
  },
  "path": "/news/:type?",
  "radar": [
    {
      "source": [
        "news.wfu.edu.cn/"
      ],
      "target": "/news"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "news.wfu.edu.cn/"
}
```
