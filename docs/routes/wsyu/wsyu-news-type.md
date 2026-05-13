# 武昌首义学院 - 新闻中心

## Coverage
`index-only`

## Route
- Namespace: `wsyu`
- Namespace Name: `武昌首义学院`
- Route Path: `/wsyu/news/:type?`
- Route Name: `新闻中心`
- Example: `/wsyu/news/xxyw`
- URL: `www.wsyu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `Derekmini`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
| 学校要闻 | 综合新闻 | 媒体聚焦 |
| -------- | -------- | -------- |
| xxyw     | zhxw     | mtjj     |

## Parameters
- `type`: 分类，默认为 `xxyw`


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
    "university"
  ],
  "description": "| 学校要闻 | 综合新闻 | 媒体聚焦 |\n| -------- | -------- | -------- |\n| xxyw     | zhxw     | mtjj     |",
  "example": "/wsyu/news/xxyw",
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
    "Derekmini"
  ],
  "name": "新闻中心",
  "parameters": {
    "type": "分类，默认为 `xxyw`"
  },
  "path": "/news/:type?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
