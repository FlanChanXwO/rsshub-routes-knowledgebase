# MakerWorld - User Uploads

## Coverage
`index-only`

## Route
- Namespace: `makerworld`
- Namespace Name: `MakerWorld`
- Route Path: `/makerworld/user/:handle/upload`
- Route Name: `User Uploads`
- Example: `/makerworld/user/@Wcad00/upload`
- URL: `makerworld.com`
- Language: `_None_`
- Categories: `design`
- Maintainers: `TonyRL`
- Source Location: `user-upload.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `handle`: User handle


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `makerworld.com/:lang/:handle/upload`
  - `makerworld.com/:lang/:handle`

## Raw JSON
```json
{
  "categories": [
    "design"
  ],
  "example": "/makerworld/user/@Wcad00/upload",
  "heat": 0,
  "location": "user-upload.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "User Uploads",
  "parameters": {
    "handle": "User handle"
  },
  "path": "/user/:handle/upload",
  "radar": [
    {
      "source": [
        "makerworld.com/:lang/:handle/upload",
        "makerworld.com/:lang/:handle"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
