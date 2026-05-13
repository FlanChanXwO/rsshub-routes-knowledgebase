# AP News - News (from mobile client API)

## Coverage
`index-only`

## Route
- Namespace: `apnews`
- Namespace Name: `AP News`
- Route Path: `/apnews/mobile/:path{.+}?`
- Route Name: `News (from mobile client API)`
- Example: `/apnews/mobile/ap-top-news`
- URL: `apnews.com`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `dzx-dzx`
- Source Location: `mobile-api.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `path`: {"default": "ap-top-news", "description": "Corresponding path from AP News website"}


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
  - `apnews.com/`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/apnews/mobile/ap-top-news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "mobile-api.ts",
  "maintainers": [
    "dzx-dzx"
  ],
  "name": "News (from mobile client API)",
  "parameters": {
    "path": {
      "default": "ap-top-news",
      "description": "Corresponding path from AP News website"
    }
  },
  "path": "/mobile/:path{.+}?",
  "radar": [
    {
      "source": [
        "apnews.com/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "view": 0
}
```
