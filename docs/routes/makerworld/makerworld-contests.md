# MakerWorld - Contests

## Coverage
`index-only`

## Route
- Namespace: `makerworld`
- Namespace Name: `MakerWorld`
- Route Path: `/makerworld/contests`
- Route Name: `Contests`
- Example: `/makerworld/contests`
- URL: `makerworld.com`
- Language: `_None_`
- Categories: `design`
- Maintainers: `TonyRL`
- Source Location: `contest.ts`
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
  - `makerworld.com/:lang/contests`

## Raw JSON
```json
{
  "categories": [
    "design"
  ],
  "example": "/makerworld/contests",
  "heat": 3,
  "location": "contest.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "Contests",
  "path": "/contests",
  "radar": [
    {
      "source": [
        "makerworld.com/:lang/contests"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Join the contest to showcase your creativity and win substantial rewards - Powered by RSSHub",
      "errorAt": "2025-11-26T08:30:24.872Z",
      "errorMessage": "[GET] \"https://makerworld.com/en\": 403 Forbidden\n",
      "id": "159773347494824960",
      "image": "https://makerworld.com/favicon_new.png",
      "ownerUserId": null,
      "siteUrl": "https://makerworld.com/en/contests",
      "title": "Contest - MakerWorld",
      "type": "feed",
      "url": "rsshub://makerworld/contests"
    }
  ]
}
```
