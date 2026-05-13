# 北京大学 - 生命科学学院通知公告

## Coverage
`index-only`

## Route
- Namespace: `pku`
- Namespace Name: `北京大学`
- Route Path: `/pku/cls/announcement`
- Route Name: `生命科学学院通知公告`
- Example: `/pku/cls/announcement`
- URL: `bio.pku.edu.cn/homes/Index/news/21/21.html`
- Language: `_None_`
- Categories: `university`
- Maintainers: `william-swl`
- Source Location: `cls/announcement.ts`
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
  - `bio.pku.edu.cn/homes/Index/news/21/21.html`
  - `bio.pku.edu.cn/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/pku/cls/announcement",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "cls/announcement.ts",
  "maintainers": [
    "william-swl"
  ],
  "name": "生命科学学院通知公告",
  "parameters": {},
  "path": "/cls/announcement",
  "radar": [
    {
      "source": [
        "bio.pku.edu.cn/homes/Index/news/21/21.html",
        "bio.pku.edu.cn/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "bio.pku.edu.cn/homes/Index/news/21/21.html"
}
```
