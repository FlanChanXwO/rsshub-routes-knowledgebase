# 轻小说文库 - 章节

## Coverage
`index-only`

## Route
- Namespace: `wenku8`
- Namespace Name: `轻小说文库`
- Route Path: `/wenku8/chapter/:id`
- Route Name: `章节`
- Example: `/wenku8/chapter/74`
- URL: `www.wenku8.net`
- Language: `_None_`
- Categories: `reading`
- Maintainers: `zsakvo`
- Source Location: `chapter.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 小说 id, 可在对应小说页 URL 中找到


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "reading"
  ],
  "example": "/wenku8/chapter/74",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 8,
  "location": "chapter.ts",
  "maintainers": [
    "zsakvo"
  ],
  "name": "章节",
  "parameters": {
    "id": "小说 id, 可在对应小说页 URL 中找到"
  },
  "path": "/chapter/:id",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "轻小说文库 声音x魔法 - Powered by RSSHub",
      "errorAt": "2025-06-04T05:27:58.200Z",
      "errorMessage": "[GET] \"https://www.wenku8.net/novel/0/74/index.htm\": 403 Forbidden\n",
      "id": "76251619421446144",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.wenku8.net/book/74.htm",
      "title": "轻小说文库 声音x魔法",
      "type": "feed",
      "url": "rsshub://wenku8/chapter/74"
    },
    {
      "description": "轻小说文库 败北女角太多了！(败犬女主太多了！) - Powered by RSSHub",
      "errorAt": "2025-08-04T14:51:43.376Z",
      "errorMessage": "[GET] \"https://www.wenku8.net/novel/3/3057/index.htm\": 403 Forbidden\n",
      "id": "65806527222285312",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.wenku8.net/book/3057.htm",
      "title": "轻小说文库 败北女角太多了！(败犬女主太多了！)",
      "type": "feed",
      "url": "rsshub://wenku8/chapter/3057"
    }
  ]
}
```
