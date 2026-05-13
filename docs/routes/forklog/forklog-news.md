# Forklog - Новости

## Coverage
`index-only`

## Route
- Namespace: `forklog`
- Namespace Name: `Forklog`
- Route Path: `/forklog/news`
- Route Name: `Новости`
- Example: `/forklog/news`
- URL: `forklog.com/news`
- Language: `_None_`
- Categories: `finance`
- Maintainers: `raven428`
- Source Location: `index.ts`
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
  - `forklog.com/news`
- `target`: `/news`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/forklog/news",
  "heat": 4,
  "location": "index.ts",
  "maintainers": [
    "raven428"
  ],
  "name": "Новости",
  "path": "/news",
  "radar": [
    {
      "source": [
        "forklog.com/news"
      ],
      "target": "/news"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Последние новости из мира блокчейна и криптовалют - Powered by RSSHub",
      "errorAt": "2026-03-24T22:21:22.261Z",
      "errorMessage": "[POST] \"https://forklog.com/wp-content/themes/forklogv2/ajax/getPosts.php\": 404 Not Found\n",
      "id": "118816637391308800",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://forklog.com/news",
      "title": "Forklog – Новости",
      "type": "feed",
      "url": "rsshub://forklog/news"
    }
  ],
  "url": "forklog.com/news"
}
```
