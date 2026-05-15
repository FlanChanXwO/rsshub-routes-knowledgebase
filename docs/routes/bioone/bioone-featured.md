# BioOne - Featured articles

## Coverage
`index-only`

## Route
- Namespace: `bioone`
- Namespace Name: `BioOne`
- Route Path: `/bioone/featured`
- Route Name: `Featured articles`
- Example: `/bioone/featured`
- URL: `bioone.org/`
- Language: `_None_`
- Categories: `journal`
- Maintainers: `nczitzk`
- Source Location: `featured.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


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
  - `bioone.org/`

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "example": "/bioone/featured",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 8,
  "location": "featured.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Featured articles",
  "parameters": {},
  "path": "/featured",
  "radar": [
    {
      "source": [
        "bioone.org/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Featured articles - BioOne - Powered by RSSHub",
      "errorAt": "2026-05-09T02:53:10.551Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "56553335105003520",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://bioone.org/",
      "title": "Featured articles - BioOne",
      "type": "feed",
      "url": "rsshub://bioone/featured"
    }
  ],
  "url": "bioone.org/"
}
```
