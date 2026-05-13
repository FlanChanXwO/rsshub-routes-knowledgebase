# ProjectJAV - Actress

## Coverage
`index-only`

## Route
- Namespace: `projectjav`
- Namespace Name: `ProjectJAV`
- Route Path: `/projectjav/actress/:id`
- Route Name: `Actress`
- Example: `/projectjav/actress/rima-arai-22198`
- URL: `projectjav.com/`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `Exat1979`
- Source Location: `actress.ts`
- Source Module: `_None_`

## Description
Fetches the latest movies from a specific actress page on ProjectJAV.

## Parameters
- `id`: Actress ID or slug, can be found in the actress page URL


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `projectjav.com/actress/:id`
- `target`: `/actress/:id`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "description": "Fetches the latest movies from a specific actress page on ProjectJAV.",
  "example": "/projectjav/actress/rima-arai-22198",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "actress.ts",
  "maintainers": [
    "Exat1979"
  ],
  "name": "Actress",
  "parameters": {
    "id": "Actress ID or slug, can be found in the actress page URL"
  },
  "path": "/actress/:id",
  "radar": [
    {
      "source": [
        "projectjav.com/actress/:id"
      ],
      "target": "/actress/:id"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "projectjav.com/"
}
```
