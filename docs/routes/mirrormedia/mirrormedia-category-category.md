# 鏡週刊 Mirror Media - 分类

## Coverage
`index-only`

## Route
- Namespace: `mirrormedia`
- Namespace Name: `鏡週刊 Mirror Media`
- Route Path: `/mirrormedia/category/:category`
- Route Name: `分类`
- Example: `/mirrormedia/category/political`
- URL: `mirrormedia.mg`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `dzx-dzx`
- Source Location: `category.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `category`: 分类名
- `section`: 子板名


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `mirrormedia.mg/category/:category`
  - `mirrormedia.mg/section/:section`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/mirrormedia/category/political",
  "heat": 35,
  "location": "category.ts",
  "maintainers": [
    "dzx-dzx"
  ],
  "name": "分类",
  "parameters": {
    "category": "分类名",
    "section": "子板名"
  },
  "path": [
    "/category/:category",
    "/section/:section"
  ],
  "radar": [
    {
      "source": [
        "mirrormedia.mg/category/:category",
        "mirrormedia.mg/section/:section"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "Error: STACK_TRACE_ERROR\n    at task (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1784:27)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1817:16)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1563:28)\n    at chain (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:599:14)\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:74:12\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:40\n    at runWithSuite (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:2258:8)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:10)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1893:54)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)"
  },
  "topFeeds": [
    {
      "description": "鏡週刊 Mirror Media - political - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "57027261715751936",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.mirrormedia.mg/",
      "title": "鏡週刊 Mirror Media - political",
      "type": "feed",
      "url": "rsshub://mirrormedia/category/political"
    },
    {
      "description": "鏡週刊 Mirror Media - city-news - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "131968010464549888",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.mirrormedia.mg/",
      "title": "鏡週刊 Mirror Media - city-news",
      "type": "feed",
      "url": "rsshub://mirrormedia/category/city-news"
    }
  ]
}
```
