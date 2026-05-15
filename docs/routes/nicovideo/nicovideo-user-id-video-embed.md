# Niconico - User Videos

## Coverage
`index-only`

## Route
- Namespace: `nicovideo`
- Namespace Name: `Niconico`
- Route Path: `/nicovideo/user/:id/video/:embed?`
- Route Name: `User Videos`
- Example: `/nicovideo/user/16690815/video`
- URL: `www.nicovideo.jp`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `TonyRL`
- Source Location: `video.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: User ID
- `embed`: Default to embed the video, set to any value to disable embedding


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.nicovideo.jp/user/:id`
  - `www.nicovideo.jp/user/:id/video`
- `target`: `/user/:id/video`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/nicovideo/user/16690815/video",
  "heat": 47,
  "location": "video.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "User Videos",
  "parameters": {
    "embed": "Default to embed the video, set to any value to disable embedding",
    "id": "User ID"
  },
  "path": "/user/:id/video/:embed?",
  "radar": [
    {
      "source": [
        "www.nicovideo.jp/user/:id",
        "www.nicovideo.jp/user/:id/video"
      ],
      "target": "/user/:id/video"
    }
  ],
  "test": {
    "code": 1,
    "message": "Error: STACK_TRACE_ERROR\n    at task (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1784:27)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1817:16)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1563:28)\n    at chain (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:599:14)\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:74:12\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:40\n    at runWithSuite (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:2258:8)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:10)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1893:54)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)"
  },
  "topFeeds": [
    {
      "description": "ピノキオピー - ニコニコ - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "67834533653006336",
      "image": "https://secure-dcdn.cdn.nimg.jp/nicoaccount/usericon/86/865591.jpg?1692257539",
      "ownerUserId": null,
      "siteUrl": "https://www.nicovideo.jp/user/865591/video",
      "title": "ピノキオピー - ニコニコ",
      "type": "feed",
      "url": "rsshub://nicovideo/user/865591/video"
    },
    {
      "description": "十六夜カズヤP - ニコニコ - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "173365214757950464",
      "image": "https://secure-dcdn.cdn.nimg.jp/nicoaccount/usericon/321/3219731.jpg?1422604697",
      "ownerUserId": null,
      "siteUrl": "https://www.nicovideo.jp/user/3219731/video",
      "title": "十六夜カズヤP - ニコニコ",
      "type": "feed",
      "url": "rsshub://nicovideo/user/3219731/video"
    }
  ]
}
```
