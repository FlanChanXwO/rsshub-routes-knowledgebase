# Typora - Dev Release Changelog

## Coverage
`index-only`

## Route
- Namespace: `typora`
- Namespace Name: `Typora`
- Route Path: `/typora/changelog/dev`
- Route Name: `Dev Release Changelog`
- Example: `/typora/changelog/dev`
- URL: `support.typora.io/`
- Language: `_None_`
- Categories: `program-update`
- Maintainers: `nczitzk`
- Source Location: `changelog-dev.ts`
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
- `target`: `/changelog`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "example": "/typora/changelog/dev",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "changelog-dev.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Dev Release Changelog",
  "parameters": {},
  "path": "/changelog/dev",
  "radar": [
    {
      "source": [
        "support.typora.io/"
      ],
      "target": "/changelog"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected [ …(9) ] to not include 'https://typora.io/releases/dev#1.8.3-…'\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.6/node_modules/@vitest/expect/dist/index.js:1319:15)\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.6/node_modules/@vitest/expect/dist/index.js:1156:15)\n    at Proxy.methodWrapper (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/chai@6.2.2/node_modules/chai/index.js:1700:25)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:67:27)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:82:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "support.typora.io/"
}
```
