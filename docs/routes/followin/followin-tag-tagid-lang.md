# Followin - Tag

## Coverage
`index-only`

## Route
- Namespace: `followin`
- Namespace Name: `Followin`
- Route Path: `/followin/tag/:tagId/:lang?`
- Route Name: `Tag`
- Example: `/followin/tag/177008`
- URL: `followin.io`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `TonyRL`
- Source Location: `tag.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `tagId`: Tag ID, can be found in URL
- `lang`: Language, see table above, `en` by default


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
  - `followin.io/:lang/tag/:tagId`
  - `followin.io/tag/:tagId`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/followin/tag/177008",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "tag.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "Tag",
  "parameters": {
    "lang": "Language, see table above, `en` by default",
    "tagId": "Tag ID, can be found in URL"
  },
  "path": "/tag/:tagId/:lang?",
  "radar": [
    {
      "source": [
        "followin.io/:lang/tag/:tagId",
        "followin.io/tag/:tagId"
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
