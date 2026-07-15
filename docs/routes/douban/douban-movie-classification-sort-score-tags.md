# 豆瓣 - 豆瓣电影分类

## Coverage
`index-only`

## Route
- Namespace: `douban`
- Namespace Name: `豆瓣`
- Route Path: `/douban/movie/classification/:sort?/:score?/:tags?`
- Route Name: `豆瓣电影分类`
- Example: `/douban/movie/classification/R/7.5/Netflix,2020`
- URL: `www.douban.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `zzwab`
- Source Location: `other/classification.ts`
- Source Module: `_None_`

## Description
排序方式可选值如下

| 近期热门 | 标记最多 | 评分最高 | 最近上映 |
| -------- | -------- | -------- | -------- |
| U        | T        | S        | R        |

## Parameters
- `sort`: 排序方式，默认为U
- `score`: 最低评分，默认不限制
- `tags`: 分类标签，多个标签之间用英文逗号分隔，常见的标签到豆瓣电影的分类页面查看，支持自定义标签


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
    "social-media"
  ],
  "description": "排序方式可选值如下\n\n| 近期热门 | 标记最多 | 评分最高 | 最近上映 |\n| -------- | -------- | -------- | -------- |\n| U        | T        | S        | R        |",
  "example": "/douban/movie/classification/R/7.5/Netflix,2020",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 26,
  "location": "other/classification.ts",
  "maintainers": [
    "zzwab"
  ],
  "name": "豆瓣电影分类",
  "parameters": {
    "score": "最低评分，默认不限制",
    "sort": "排序方式，默认为U",
    "tags": "分类标签，多个标签之间用英文逗号分隔，常见的标签到豆瓣电影的分类页面查看，支持自定义标签"
  },
  "path": "/movie/classification/:sort?/:score?/:tags?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at runNextTicks (node:internal/process/task_queues:69:3)\n    at processImmediate (node:internal/timers:472:9)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "豆瓣电影分类超过 7.5 分的影视 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "64117673690336325",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://movie.douban.com/tag/#/?sort=U&range=0,10&tags=",
      "title": "豆瓣电影分类超过 7.5 分的影视",
      "type": "feed",
      "url": "rsshub://douban/movie/classification/R/7.5/%25E7%25A7%2591%25E5%25B9%25BB"
    },
    {
      "description": "豆瓣电影分类影视 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "155307226993530880",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://movie.douban.com/tag/#/?sort=U&range=0,10&tags=",
      "title": "豆瓣电影分类影视",
      "type": "feed",
      "url": "rsshub://douban/movie/classification"
    }
  ]
}
```
