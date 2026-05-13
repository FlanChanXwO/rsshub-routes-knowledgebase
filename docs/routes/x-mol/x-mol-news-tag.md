# X-MOL - News

## Coverage
`index-only`

## Route
- Namespace: `x-mol`
- Namespace Name: `X-MOL`
- Route Path: `/x-mol/news/:tag?`
- Route Name: `News`
- Example: `/x-mol/news/3`
- URL: `x-mol.com/news/index`
- Language: `_None_`
- Categories: `study`
- Maintainers: `cssxsh`
- Source Location: `news.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `tag`: Tag number, can be obtained from news list URL. Empty value means news index.


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
  - `x-mol.com/news/index`
- `target`: `/news`

## Raw JSON
```json
{
  "categories": [
    "study"
  ],
  "example": "/x-mol/news/3",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 7,
  "location": "news.tsx",
  "maintainers": [
    "cssxsh"
  ],
  "name": "News",
  "parameters": {
    "tag": "Tag number, can be obtained from news list URL. Empty value means news index."
  },
  "path": "/news/:tag?",
  "radar": [
    {
      "source": [
        "x-mol.com/news/index"
      ],
      "target": "/news"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "xmol.newsIndex.orderBy.webDescription - Powered by RSSHub",
      "errorAt": "2026-01-19T11:31:03.378Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "104705301345654802",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://docs.rsshub.app/",
      "title": "化学/材料,材料行业资讯 - X-MOL",
      "type": "feed",
      "url": "rsshub://x-mol/news/16"
    },
    {
      "description": "xmol.newsIndex.orderBy.webDescription - Powered by RSSHub",
      "errorAt": "2025-10-29T15:08:39.212Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "75714788213579777",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://docs.rsshub.app/",
      "title": "化学/材料,药物与医疗行业资讯 - X-MOL",
      "type": "feed",
      "url": "rsshub://x-mol/news/3"
    }
  ],
  "url": "x-mol.com/news/index"
}
```
