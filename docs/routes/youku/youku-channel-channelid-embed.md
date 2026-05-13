# 优酷 - 频道

## Coverage
`index-only`

## Route
- Namespace: `youku`
- Namespace Name: `优酷`
- Route Path: `/youku/channel/:channelId/:embed?`
- Route Name: `频道`
- Example: `/youku/channel/UNTg3MTM3OTcy`
- URL: `i.youku.com`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `xyqfer, Fatpandac`
- Source Location: `channel.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `channelId`: 频道 id
- `embed`: 默认为开启内嵌视频, 任意值为关闭


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `i.youku.com/i/:id`
- `target`: `/channel/:id`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/youku/channel/UNTg3MTM3OTcy",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "channel.tsx",
  "maintainers": [
    "xyqfer",
    "Fatpandac"
  ],
  "name": "频道",
  "parameters": {
    "channelId": "频道 id",
    "embed": "默认为开启内嵌视频, 任意值为关闭"
  },
  "path": "/channel/:channelId/:embed?",
  "radar": [
    {
      "source": [
        "i.youku.com/i/:id"
      ],
      "target": "/channel/:id"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 'RSSHub' not to be 'RSSHub' // Object.is equality\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:45:30)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:82:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
