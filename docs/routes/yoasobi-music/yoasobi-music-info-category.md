# Yoasobi Official - News & Biography

## Coverage
`index-only`

## Route
- Namespace: `yoasobi-music`
- Namespace Name: `Yoasobi Official`
- Route Path: `/yoasobi-music/info/:category?`
- Route Name: `News & Biography`
- Example: `/yoasobi-music/info/news`
- URL: `www.yoasobi-music.jp/`
- Language: `_None_`
- Categories: `live`
- Maintainers: `None`
- Source Location: `info.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `category`: `news`, `biography`


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
  - `www.yoasobi-music.jp/`
  - `www.yoasobi-music.jp/:category`
- `target`: `/info/:category`

## Raw JSON
```json
{
  "categories": [
    "live"
  ],
  "example": "/yoasobi-music/info/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 7,
  "location": "info.tsx",
  "maintainers": [],
  "name": "News & Biography",
  "parameters": {
    "category": "`news`, `biography`"
  },
  "path": "/info/:category?",
  "radar": [
    {
      "source": [
        "www.yoasobi-music.jp/",
        "www.yoasobi-music.jp/:category"
      ],
      "target": "/info/:category"
    }
  ],
  "test": {
    "code": 1,
    "message": "Error: STACK_TRACE_ERROR\n    at task (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1784:27)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1817:16)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1563:28)\n    at chain (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:599:14)\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:74:12\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:40\n    at runWithSuite (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:2258:8)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:10)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1893:54)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)"
  },
  "topFeeds": [
    {
      "description": "Yoasobi's latest biography - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "59199683879800832",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.yoasobi-music.jp/biography",
      "title": "LATEST BIOGRAPHY",
      "type": "feed",
      "url": "rsshub://yoasobi-music/info/biography"
    },
    {
      "description": "Yoasobi's latest news - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "59198663955091456",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.yoasobi-music.jp/news",
      "title": "LATEST NEWS",
      "type": "feed",
      "url": "rsshub://yoasobi-music/info/news"
    }
  ],
  "url": "www.yoasobi-music.jp/"
}
```
