# Google - Research Blog

## Coverage
`index-only`

## Route
- Namespace: `google`
- Namespace Name: `Google`
- Route Path: `/google/research`
- Route Name: `Research Blog`
- Example: `/google/research`
- URL: `www.google.com`
- Language: `_None_`
- Categories: `blog`
- Maintainers: `Levix, cscnk52`
- Source Location: `research.ts`
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
  - `research.google`

## Raw JSON
```json
{
  "categories": [
    "blog"
  ],
  "example": "/google/research",
  "heat": 882,
  "location": "research.ts",
  "maintainers": [
    "Levix",
    "cscnk52"
  ],
  "name": "Research Blog",
  "path": "/research",
  "radar": [
    {
      "source": [
        "research.google"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected NaN to be greater than -432000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:37:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:63:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:82:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Google Research Blog - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "56446234310693888",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://research.google/blog",
      "title": "Google Research Blog",
      "type": "feed",
      "url": "rsshub://google/research"
    }
  ]
}
```
