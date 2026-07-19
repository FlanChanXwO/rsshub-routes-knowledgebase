# AInvest - Latest Article

## Coverage
`index-only`

## Route
- Namespace: `ainvest`
- Namespace Name: `AInvest`
- Route Path: `/ainvest/article`
- Route Name: `Latest Article`
- Example: `/ainvest/article`
- URL: `www.ainvest.com/news/articles-latest/`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `TonyRL`
- Source Location: `article.ts`
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
  - `www.ainvest.com/news/articles-latest/`
  - `www.ainvest.com`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/ainvest/article",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 13,
  "location": "article.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "Latest Article",
  "parameters": {},
  "path": "/article",
  "radar": [
    {
      "source": [
        "www.ainvest.com/news/articles-latest/",
        "www.ainvest.com"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "AInvest - Latest Articles - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "165445337069434882",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.ainvest.com/news/articles-latest/",
      "title": "AInvest - Latest Articles",
      "type": "feed",
      "url": "rsshub://ainvest/article"
    }
  ],
  "url": "www.ainvest.com/news/articles-latest/"
}
```
