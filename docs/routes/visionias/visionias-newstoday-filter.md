# VisionIAS - News Today

## Coverage
`index-only`

## Route
- Namespace: `visionias`
- Namespace Name: `VisionIAS`
- Route Path: `/visionias/newsToday/:filter?`
- Route Name: `News Today`
- Example: `/visionias/newsToday`
- URL: `visionias.in`
- Language: `_None_`
- Categories: `study`
- Maintainers: `Rjnishant530`
- Source Location: `news-today.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `filter`: {"default": "latest", "description": "Period to fetch news for the current month. All news for the current month or only the latest", "options": [{"label": "All", "value": "all"}, {"label": "Latest", "value": "latest"}]}


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
  - `visionias.in/current-affairs/news-today`
- `target`: `/newsToday`

## Raw JSON
```json
{
  "categories": [
    "study"
  ],
  "example": "/visionias/newsToday",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "news-today.ts",
  "maintainers": [
    "Rjnishant530"
  ],
  "name": "News Today",
  "parameters": {
    "filter": {
      "default": "latest",
      "description": "Period to fetch news for the current month. All news for the current month or only the latest",
      "options": [
        {
          "label": "All",
          "value": "all"
        },
        {
          "label": "Latest",
          "value": "latest"
        }
      ]
    }
  },
  "path": "/newsToday/:filter?",
  "radar": [
    {
      "source": [
        "visionias.in/current-affairs/news-today"
      ],
      "target": "/newsToday"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected [ 'Error Parse News' ] to not include 'Error Parse News'\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.6/node_modules/@vitest/expect/dist/index.js:1319:15)\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.6/node_modules/@vitest/expect/dist/index.js:1156:15)\n    at Proxy.methodWrapper (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/chai@6.2.2/node_modules/chai/index.js:1700:25)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:67:27)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:82:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
