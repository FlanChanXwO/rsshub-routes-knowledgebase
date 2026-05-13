# 北京大学 - 生命科学学院近期讲座

## Coverage
`index-only`

## Route
- Namespace: `pku`
- Namespace Name: `北京大学`
- Route Path: `/pku/cls/lecture`
- Route Name: `生命科学学院近期讲座`
- Example: `/pku/cls/lecture`
- URL: `bio.pku.edu.cn/homes/Index/news_jz/7/7.html`
- Language: `_None_`
- Categories: `university`
- Maintainers: `TPOB`
- Source Location: `cls/lecture.ts`
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
  - `bio.pku.edu.cn/homes/Index/news_jz/7/7.html`
  - `bio.pku.edu.cn/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "example": "/pku/cls/lecture",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 5,
  "location": "cls/lecture.ts",
  "maintainers": [
    "TPOB"
  ],
  "name": "生命科学学院近期讲座",
  "parameters": {},
  "path": "/cls/lecture",
  "radar": [
    {
      "source": [
        "bio.pku.edu.cn/homes/Index/news_jz/7/7.html",
        "bio.pku.edu.cn/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "北京大学生命科学学院近期讲座 - Powered by RSSHub",
      "errorAt": "2026-02-02T08:24:21.353Z",
      "errorMessage": "[GET] \"http://bio.pku.edu.cn/homes/Index/news_jz/7/7.html\": <no response> fetch failed\nFailed to fetch\n",
      "id": "178730120580722688",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://bio.pku.edu.cn/homes/Index/news_jz/7/7.html",
      "title": "北京大学生命科学学院近期讲座",
      "type": "feed",
      "url": "rsshub://pku/cls/lecture"
    }
  ],
  "url": "bio.pku.edu.cn/homes/Index/news_jz/7/7.html"
}
```
