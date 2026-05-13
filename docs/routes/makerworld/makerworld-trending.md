# MakerWorld - Trending Models

## Coverage
`index-only`

## Route
- Namespace: `makerworld`
- Namespace Name: `MakerWorld`
- Route Path: `/makerworld/trending`
- Route Name: `Trending Models`
- Example: `/makerworld/trending`
- URL: `makerworld.com`
- Language: `_None_`
- Categories: `design`
- Maintainers: `TonyRL`
- Source Location: `trending.ts`
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
  - `makerworld.com/:lang`

## Raw JSON
```json
{
  "categories": [
    "design"
  ],
  "example": "/makerworld/trending",
  "heat": 60,
  "location": "trending.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "Trending Models",
  "path": "/trending",
  "radar": [
    {
      "source": [
        "makerworld.com/:lang"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Leading 3D printing model community for designers and makers. Download thousands of 3D models and stl models for free, and your No.1 option for multicolor 3D models - Powered by RSSHub",
      "errorAt": "2025-11-26T09:55:42.967Z",
      "errorMessage": "[GET] \"https://makerworld.com/en\": 403 Forbidden\n",
      "id": "159773156338176000",
      "image": "https://makerworld.com/favicon_new.png",
      "ownerUserId": null,
      "siteUrl": "https://makerworld.com/en",
      "title": "Trending Models - MakerWorld",
      "type": "feed",
      "url": "rsshub://makerworld/trending"
    }
  ]
}
```
