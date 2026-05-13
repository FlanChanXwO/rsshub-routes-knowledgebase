# Windsurf - Changelog

## Coverage
`index-only`

## Route
- Namespace: `windsurf`
- Namespace Name: `Windsurf`
- Route Path: `/windsurf/changelog`
- Route Name: `Changelog`
- Example: `/windsurf/changelog`
- URL: `windsurf.com`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `nczitzk`
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
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `windsurf.com/changelog`
- `target`: `/changelog`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/windsurf/changelog",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 17,
  "location": "changelog.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Changelog",
  "path": "/changelog",
  "radar": [
    {
      "source": [
        "windsurf.com/changelog"
      ],
      "target": "/changelog"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected [ 'windsurf-2.2.17', …(7) ] to not include 'https://windsurf.com/changelog'\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.6/node_modules/@vitest/expect/dist/index.js:1319:15)\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.6/node_modules/@vitest/expect/dist/index.js:1156:15)\n    at Proxy.methodWrapper (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/chai@6.2.2/node_modules/chai/index.js:1700:25)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:67:27)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:82:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Latest updates and changes for the Windsurf Editor. - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "159056464110272512",
      "image": "https://exafunction.github.io/public/images/website_thumbnails/changelog.jpg",
      "ownerUserId": null,
      "siteUrl": "https://windsurf.com/changelog",
      "title": "Discord",
      "type": "feed",
      "url": "rsshub://windsurf/changelog"
    }
  ],
  "url": "windsurf.com",
  "view": 0
}
```
