# MissKON - Top k days

## Coverage
`index-only`

## Route
- Namespace: `misskon`
- Namespace Name: `MissKON`
- Route Path: `/misskon/top/:k`
- Route Name: `Top k days`
- Example: `/misskon/top/60`
- URL: `misskon.com`
- Language: `_None_`
- Categories: `picture`
- Maintainers: `Urabartin`
- Source Location: `top.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `k`: Top k days, can be 3, 7, 30 or 60


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
### Rule 1
- `title`: `Top 3 days`
- `source`:
  - `misskon.com/top3/`
- `target`: `/top/3`
### Rule 2
- `title`: `Top 7 days`
- `source`:
  - `misskon.com/top7/`
- `target`: `/top/7`
### Rule 3
- `title`: `Top 30 days`
- `source`:
  - `misskon.com/top30/`
- `target`: `/top/30`
### Rule 4
- `title`: `Top 60 days`
- `source`:
  - `misskon.com/top60/`
- `target`: `/top/60`

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "example": "/misskon/top/60",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 369,
  "location": "top.ts",
  "maintainers": [
    "Urabartin"
  ],
  "name": "Top k days",
  "parameters": {
    "k": "Top k days, can be 3, 7, 30 or 60"
  },
  "path": "/top/:k",
  "radar": [
    {
      "source": [
        "misskon.com/top3/"
      ],
      "target": "/top/3",
      "title": "Top 3 days"
    },
    {
      "source": [
        "misskon.com/top7/"
      ],
      "target": "/top/7",
      "title": "Top 7 days"
    },
    {
      "source": [
        "misskon.com/top30/"
      ],
      "target": "/top/30",
      "title": "Top 30 days"
    },
    {
      "source": [
        "misskon.com/top60/"
      ],
      "target": "/top/60",
      "title": "Top 60 days"
    }
  ],
  "test": {
    "code": 1,
    "message": "Error: STACK_TRACE_ERROR\n    at task (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1784:27)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1817:16)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1563:28)\n    at chain (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:599:14)\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:74:12\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:40\n    at runWithSuite (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:2258:8)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:10)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1893:54)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)"
  },
  "topFeeds": [
    {
      "description": "The most viewed photos in the past 2 months. - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "70259303892775936",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://misskon.com/top60/",
      "title": "MissKON - Top 60 days",
      "type": "feed",
      "url": "rsshub://misskon/top/60"
    },
    {
      "description": "The most viewed photos of the past week. - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "75526635626105856",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://misskon.com/top7/",
      "title": "MissKON - Top 7 days",
      "type": "feed",
      "url": "rsshub://misskon/top/7"
    }
  ]
}
```
