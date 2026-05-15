# 中文成人文學網 - 短篇

## Coverage
`index-only`

## Route
- Namespace: `xbookcn`
- Namespace Name: `中文成人文學網`
- Route Path: `/xbookcn/:label?`
- Route Name: `短篇`
- Example: `/xbookcn/精选作品`
- URL: `www.xbookcn.net`
- Language: `_None_`
- Categories: `reading, popular`
- Maintainers: `Lyunvy`
- Source Location: `blog.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `label`: 按名称分类，详见https://blog.xbookcn.net/p/all.html


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "reading",
    "popular"
  ],
  "example": "/xbookcn/精选作品",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1800,
  "location": "blog.ts",
  "maintainers": [
    "Lyunvy"
  ],
  "name": "短篇",
  "parameters": {
    "label": "按名称分类，详见https://blog.xbookcn.net/p/all.html"
  },
  "path": "/:label?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "xbookcn - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "66735517584488448",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://blog.xbookcn.net/search/label/%E7%B2%BE%E9%80%89%E4%BD%9C%E5%93%81",
      "title": "xbookcn",
      "type": "feed",
      "url": "rsshub://xbookcn"
    },
    {
      "description": "xbookcn - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "65082601526572032",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://blog.xbookcn.net/search/label/%E7%B2%BE%E9%80%89%E4%BD%9C%E5%93%81",
      "title": "xbookcn",
      "type": "feed",
      "url": "rsshub://xbookcn/%E7%B2%BE%E9%80%89%E4%BD%9C%E5%93%81"
    }
  ]
}
```
