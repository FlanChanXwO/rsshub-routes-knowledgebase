# VisionIAS - Monthly Magazine

## Coverage
`index-only`

## Route
- Namespace: `visionias`
- Namespace Name: `VisionIAS`
- Route Path: `/visionias/monthlyMagazine`
- Route Name: `Monthly Magazine`
- Example: `/visionias/monthlyMagazine`
- URL: `visionias.in`
- Language: `_None_`
- Categories: `study`
- Maintainers: `Rjnishant530`
- Source Location: `monthly-magazine.ts`
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
  - `visionias.in/current-affairs/monthly-magazine`
- `target`: `/monthlyMagazine`

## Raw JSON
```json
{
  "categories": [
    "study"
  ],
  "example": "/visionias/monthlyMagazine",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "monthly-magazine.ts",
  "maintainers": [
    "Rjnishant530"
  ],
  "name": "Monthly Magazine",
  "path": "/monthlyMagazine",
  "radar": [
    {
      "source": [
        "visionias.in/current-affairs/monthly-magazine"
      ],
      "target": "/monthlyMagazine"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected [ 'Error Parse News' ] to not include 'Error Parse News'\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.6/node_modules/@vitest/expect/dist/index.js:1319:15)\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.6/node_modules/@vitest/expect/dist/index.js:1156:15)\n    at Proxy.methodWrapper (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/chai@6.2.2/node_modules/chai/index.js:1700:25)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:67:27)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:82:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
