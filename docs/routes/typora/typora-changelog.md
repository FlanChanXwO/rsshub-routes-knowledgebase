# Typora - Changelog

## Coverage
`index-only`

## Route
- Namespace: `typora`
- Namespace Name: `Typora`
- Route Path: `/typora/changelog`
- Route Name: `Changelog`
- Example: `/typora/changelog`
- URL: `support.typora.io/`
- Language: `_None_`
- Categories: `program-update`
- Maintainers: `cnzgray`
- Source Location: `changelog.ts`
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
  - `support.typora.io/`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "example": "/typora/changelog",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 18,
  "location": "changelog.ts",
  "maintainers": [
    "cnzgray"
  ],
  "name": "Changelog",
  "parameters": {},
  "path": "/changelog",
  "radar": [
    {
      "source": [
        "support.typora.io/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected NaN to be greater than -432000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:37:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:63:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:82:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Typora Changelog - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "62127284244303872",
      "image": "https://support.typora.io/assets/img/favicon-128.png",
      "ownerUserId": null,
      "siteUrl": "https://support.typora.io/",
      "title": "Typora Changelog",
      "type": "feed",
      "url": "rsshub://typora/changelog"
    }
  ],
  "url": "support.typora.io/"
}
```
