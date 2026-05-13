# ZAKER - 精读

## Coverage
`index-only`

## Route
- Namespace: `zaker`
- Namespace Name: `ZAKER`
- Route Path: `/zaker/focusread`
- Route Name: `精读`
- Example: `/zaker/focusread`
- URL: `myzaker.com`
- Language: `_None_`
- Categories: `other`
- Maintainers: `AlexdanerZe, TonyRL`
- Source Location: `focus.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.myzaker.com/`
- `target`: `/focusread`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "example": "/zaker/focusread",
  "heat": 301,
  "location": "focus.ts",
  "maintainers": [
    "AlexdanerZe",
    "TonyRL"
  ],
  "name": "精读",
  "path": "/focusread",
  "radar": [
    {
      "source": [
        "www.myzaker.com/"
      ],
      "target": "/focusread"
    }
  ],
  "test": {
    "code": 1,
    "message": "Error: STACK_TRACE_ERROR\n    at task (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1784:27)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1817:16)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1563:28)\n    at chain (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:599:14)\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:74:12\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:40\n    at runWithSuite (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:2258:8)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:10)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1893:54)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)"
  },
  "topFeeds": [
    {
      "description": "ZAKER 精读新闻 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "54945423974379534",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.myzaker.com/?pos=selected_article",
      "title": "ZAKER 精读新闻",
      "type": "feed",
      "url": "rsshub://zaker/focusread"
    }
  ]
}
```
