# Oct0pu5 blog - Oct的小破站

## Coverage
`index-only`

## Route
- Namespace: `oct0pu5`
- Namespace Name: `Oct0pu5 blog`
- Route Path: `/oct0pu5/`
- Route Name: `Oct的小破站`
- Example: `/oct0pu5`
- URL: `Oct0pu5.cn`
- Language: `_None_`
- Categories: `blog`
- Maintainers: `octopus058, wiketool`
- Source Location: `rss.ts`
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
  - `oct0pu5.cn`
- `target`: `/`

## Raw JSON
```json
{
  "categories": [
    "blog"
  ],
  "example": "/oct0pu5",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "rss.ts",
  "maintainers": [
    "octopus058",
    "wiketool"
  ],
  "name": "Oct的小破站",
  "path": "/",
  "radar": [
    {
      "source": [
        "oct0pu5.cn"
      ],
      "target": "/"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
