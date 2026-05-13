# VICE - Topic

## Coverage
`index-only`

## Route
- Namespace: `vice`
- Namespace Name: `VICE`
- Route Path: `/vice/topic/:topic/:language?`
- Route Name: `Topic`
- Example: `/vice/topic/politics/en`
- URL: `vice.com/`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `K33k0`
- Source Location: `topic.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `topic`: Can be found in the URL
- `language`: defaults to `en`, use the website to discover other codes


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.vice.com/:language/topic/:topic`
- `target`: `/topic/:topic/:language`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/vice/topic/politics/en",
  "heat": 0,
  "location": "topic.tsx",
  "maintainers": [
    "K33k0"
  ],
  "name": "Topic",
  "parameters": {
    "language": "defaults to `en`, use the website to discover other codes",
    "topic": "Can be found in the URL"
  },
  "path": "/topic/:topic/:language?",
  "radar": [
    {
      "source": [
        "www.vice.com/:language/topic/:topic"
      ],
      "target": "/topic/:topic/:language"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "vice.com/"
}
```
