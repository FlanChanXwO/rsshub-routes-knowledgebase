# 广西民族大学 - 图书馆最新消息

## Coverage
`index-only`

## Route
- Namespace: `gxmzu`
- Namespace Name: `广西民族大学`
- Route Path: `/gxmzu/libzxxx`
- Route Name: `图书馆最新消息`
- Example: `/gxmzu/libzxxx`
- URL: `library.gxmzu.edu.cn/news/news_list.jsp`
- Language: `_None_`
- Categories: `university`
- Maintainers: `real-jiakai`
- Source Location: `lib.ts`
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
  - `library.gxmzu.edu.cn/news/news_list.jsp`
  - `library.gxmzu.edu.cn/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/gxmzu/libzxxx",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 2,
  "location": "lib.ts",
  "maintainers": [
    "real-jiakai"
  ],
  "name": "图书馆最新消息",
  "parameters": {},
  "path": "/libzxxx",
  "radar": [
    {
      "source": [
        "library.gxmzu.edu.cn/news/news_list.jsp",
        "library.gxmzu.edu.cn/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "广西民族大学图书馆 -- 最新消息 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "92039525158448128",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://library.gxmzu.edu.cn/news/news_list.jsp?urltype=tree.TreeTempUrl&wbtreeid=1010",
      "title": "广西民族大学图书馆 -- 最新消息",
      "type": "feed",
      "url": "rsshub://gxmzu/libzxxx"
    }
  ],
  "url": "library.gxmzu.edu.cn/news/news_list.jsp"
}
```
