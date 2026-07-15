# Futubull 富途牛牛 - 视频

## Coverage
`index-only`

## Route
- Namespace: `futunn`
- Namespace Name: `Futubull 富途牛牛`
- Route Path: `/futunn/video`
- Route Name: `视频`
- Example: `/futunn/video`
- URL: `news.futunn.com`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `kennyfong19931`
- Source Location: `video.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


## Features
- `supportRadar`: true

## Radar
### Rule 1
- `source`:
  - `news.futunn.com/main/video-list`
  - `news.futunn.com/:lang/main/video-list`
- `target`: `/video`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/futunn/video",
  "features": {
    "supportRadar": true
  },
  "heat": 0,
  "location": "video.ts",
  "maintainers": [
    "kennyfong19931"
  ],
  "name": "视频",
  "path": "/video",
  "radar": [
    {
      "source": [
        "news.futunn.com/main/video-list",
        "news.futunn.com/:lang/main/video-list"
      ],
      "target": "/video"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at runNextTicks (node:internal/process/task_queues:69:3)\n    at processImmediate (node:internal/timers:472:9)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
