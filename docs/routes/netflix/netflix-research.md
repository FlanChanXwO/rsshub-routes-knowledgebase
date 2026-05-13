# Netflix - Research

## Coverage
`index-only`

## Route
- Namespace: `netflix`
- Namespace Name: `Netflix`
- Route Path: `/netflix/research`
- Route Name: `Research`
- Example: `/netflix/research`
- URL: `research.netflix.com/`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `TonyRL`
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
  - `research.netflix.com/archive`
  - `research.netflix.com`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/netflix/research",
  "heat": 0,
  "location": "research.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "Research",
  "path": "/research",
  "radar": [
    {
      "source": [
        "research.netflix.com/archive",
        "research.netflix.com"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected [ …(97) ] to not include 'https://arxiv.org/abs/2106.15346'\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.6/node_modules/@vitest/expect/dist/index.js:1319:15)\n    at Proxy.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+expect@4.1.6/node_modules/@vitest/expect/dist/index.js:1156:15)\n    at Proxy.methodWrapper (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/chai@6.2.2/node_modules/chai/index.js:1700:25)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:67:27)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:82:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "research.netflix.com/"
}
```
