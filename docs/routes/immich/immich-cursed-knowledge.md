# Immich - Cursed Knowledge

## Coverage
`index-only`

## Route
- Namespace: `immich`
- Namespace Name: `Immich`
- Route Path: `/immich/cursed-knowledge`
- Route Name: `Cursed Knowledge`
- Example: `/immich/cursed-knowledge`
- URL: `immich.app`
- Language: `_None_`
- Categories: `blog`
- Maintainers: `TonyRL`
- Source Location: `cursed-knowledge.ts`
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
  - `immich.app/cursed-knowledge`
  - `immich.app`
- `target`: `/cursed-knowledge`

## Raw JSON
```json
{
  "categories": [
    "blog"
  ],
  "example": "/immich/cursed-knowledge",
  "heat": 2,
  "location": "cursed-knowledge.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "Cursed Knowledge",
  "path": "/cursed-knowledge",
  "radar": [
    {
      "source": [
        "immich.app/cursed-knowledge",
        "immich.app"
      ],
      "target": "/cursed-knowledge"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected [ Array(1) ] to not include 'https://immich.app/cursed-knowledge/#'\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.6/node_modules/@vitest/expect/dist/index.js:1319:15)\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.6/node_modules/@vitest/expect/dist/index.js:1156:15)\n    at Proxy.methodWrapper (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/chai@6.2.2/node_modules/chai/index.js:1700:25)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:67:27)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:82:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Cursed Knowledge | Immich - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "181238816402329600",
      "image": "https://immich.app./favicon.ico",
      "ownerUserId": null,
      "siteUrl": "https://immich.app/cursed-knowledge/",
      "title": "Cursed Knowledge | Immich",
      "type": "feed",
      "url": "rsshub://immich/cursed-knowledge"
    }
  ]
}
```
