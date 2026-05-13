# 清华大学 - 清华新闻

## Coverage
`index-only`

## Route
- Namespace: `tsinghua`
- Namespace Name: `清华大学`
- Route Path: `/tsinghua/news/:category?`
- Route Name: `清华新闻`
- Example: `/tsinghua/news`
- URL: `www.tsinghua.edu.cn/news.htm`
- Language: `_None_`
- Categories: `university`
- Maintainers: `TonyRL`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `category`: 分类，可在对应分类页 URL 中找到，留空为 `zxdt`


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
  - `www.tsinghua.edu.cn/news/:category`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/tsinghua/news",
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
    "TonyRL"
  ],
  "name": "清华新闻",
  "parameters": {
    "category": "分类，可在对应分类页 URL 中找到，留空为 `zxdt`"
  },
  "path": "/news/:category?",
  "radar": [
    {
      "source": [
        "www.tsinghua.edu.cn/news/:category"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "www.tsinghua.edu.cn/news.htm"
}
```
