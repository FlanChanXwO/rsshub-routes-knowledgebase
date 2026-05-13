# USENIX - ;login:

## Coverage
`index-only`

## Route
- Namespace: `usenix`
- Namespace Name: `USENIX`
- Route Path: `/usenix/loginonline`
- Route Name: `;login:`
- Example: `/usenix/loginonline`
- URL: `usenix.org`
- Language: `_None_`
- Categories: `journal`
- Maintainers: `wu-yufei`
- Source Location: `loginonline.ts`
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
  - `usenix.org/publications/loginonline`
  - `usenix.org/publications`
  - `usenix.org/`

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "example": "/usenix/loginonline",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 2,
  "location": "loginonline.ts",
  "maintainers": [
    "wu-yufei"
  ],
  "name": ";login:",
  "parameters": {},
  "path": "/loginonline",
  "radar": [
    {
      "source": [
        "usenix.org/publications/loginonline",
        "usenix.org/publications",
        "usenix.org/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "An open access publication driven by the USENIX community - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "68896175603201024",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.usenix.org/publications/loginonline",
      "title": "USENIX ;login:",
      "type": "feed",
      "url": "rsshub://usenix/loginonline"
    }
  ]
}
```
