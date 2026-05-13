# 6v 电影 - 最新电视剧

## Coverage
`index-only`

## Route
- Namespace: `6v123`
- Namespace Name: `6v 电影`
- Route Path: `/6v123/latestTVSeries`
- Route Name: `最新电视剧`
- Example: `/6v123/latestTVSeries`
- URL: `hao6v.com/`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `tc9011`
- Source Location: `latest-tvseries.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: true
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `hao6v.com/`
  - `hao6v.com/gvod/dsj.html`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/6v123/latestTVSeries",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": true,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 122,
  "location": "latest-tvseries.ts",
  "maintainers": [
    "tc9011"
  ],
  "name": "最新电视剧",
  "parameters": {},
  "path": "/latestTVSeries",
  "radar": [
    {
      "source": [
        "hao6v.com/",
        "hao6v.com/gvod/dsj.html"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "6v最新电影RSS - Powered by RSSHub",
      "errorAt": "2026-01-08T04:57:10.678Z",
      "errorMessage": "[GET] \"https://www.hao6v.tv/gvod/dsj.html\": <no response> fetch failed\n[GET] \"https://www.hao6v.tv/gvod/dsj.html\": <no response> fetch failed\n",
      "id": "59838106508034048",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.hao6v.tv/gvod/dsj.html",
      "title": "6v电影-最新电影",
      "type": "feed",
      "url": "rsshub://6v123/latestTVSeries"
    }
  ],
  "url": "hao6v.com/"
}
```
