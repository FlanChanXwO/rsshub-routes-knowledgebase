# MagazineLib - Latest Magazine

## Coverage
`index-only`

## Route
- Namespace: `magazinelib`
- Namespace Name: `MagazineLib`
- Route Path: `/magazinelib/latest-magazine/:query?`
- Route Name: `Latest Magazine`
- Example: `/magazinelib/latest-magazine/new+yorker`
- URL: `magazinelib.com`
- Language: `_None_`
- Categories: `reading`
- Maintainers: `EthanWng97`
- Source Location: `latest-magazine.tsx`
- Source Module: `_None_`

## Description
For instance, when doing search at <https://magazinelib.com> and you get url `https://magazinelib.com/?s=new+yorker`, the query is `new+yorker`

## Parameters
- `query`: query, search page querystring


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "reading"
  ],
  "description": "For instance, when doing search at <https://magazinelib.com> and you get url `https://magazinelib.com/?s=new+yorker`, the query is `new+yorker`",
  "example": "/magazinelib/latest-magazine/new+yorker",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "latest-magazine.tsx",
  "maintainers": [
    "EthanWng97"
  ],
  "name": "Latest Magazine",
  "parameters": {
    "query": "query, search page querystring"
  },
  "path": "/latest-magazine/:query?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "MagazineLib - Latest Magazines - NEW YORKER - Powered by RSSHub",
      "errorAt": "2026-04-28T23:31:52.332Z",
      "errorMessage": "500 Internal Server Error\n",
      "id": "258938409787591680",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "rsshub://magazinelib/latest-magazine/%7Bhost%7D/?s=new%20yorker",
      "title": "MagazineLib - Latest Magazines - NEW YORKER",
      "type": "feed",
      "url": "rsshub://magazinelib/latest-magazine/new%20yorker"
    }
  ]
}
```
