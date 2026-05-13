# The Economist - Global Business Review

## Coverage
`index-only`

## Route
- Namespace: `economist`
- Namespace Name: `The Economist`
- Route Path: `/economist/global-business-review/:language?`
- Route Name: `Global Business Review`
- Example: `/economist/global-business-review/cn-en`
- URL: `businessreview.global/`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `prnake`
- Source Location: `global-business-review.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `language`: Language, `en`, `cn`, `tw` are supported, support multiple options, default to cn-en


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
  - `businessreview.global/`
- `target`: `/global-business-review`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/economist/global-business-review/cn-en",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 6,
  "location": "global-business-review.ts",
  "maintainers": [
    "prnake"
  ],
  "name": "Global Business Review",
  "parameters": {
    "language": "Language, `en`, `cn`, `tw` are supported, support multiple options, default to cn-en"
  },
  "path": "/global-business-review/:language?",
  "radar": [
    {
      "source": [
        "businessreview.global/"
      ],
      "target": "/global-business-review"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": null,
      "errorAt": "2025-06-01T11:07:40.126Z",
      "errorMessage": "[GET] \"https://api.hummingbird.businessreview.global/api/toc/get_articles\": <no response> fetch failed\n",
      "id": "151955931879114755",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://economist/global-business-review/cn-en"
    }
  ],
  "url": "businessreview.global/"
}
```
