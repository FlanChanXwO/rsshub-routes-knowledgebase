# Crossbell - Notes of character

## Coverage
`index-only`

## Route
- Namespace: `crossbell`
- Namespace Name: `Crossbell`
- Route Path: `/crossbell/notes/character/:characterId`
- Route Name: `Notes of character`
- Example: `/crossbell/notes/character/10`
- URL: `crossbell.io/*`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `DIYgod`
- Source Location: `notes/character.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `characterId`: N


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
  - `crossbell.io/*`
- `target`: `/notes`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/crossbell/notes/character/10",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 4,
  "location": "notes/character.ts",
  "maintainers": [
    "DIYgod"
  ],
  "name": "Notes of character",
  "parameters": {
    "characterId": "N"
  },
  "path": "/notes/character/:characterId",
  "radar": [
    {
      "source": [
        "crossbell.io/*"
      ],
      "target": "/notes"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Crossbell Notes from 云野阁 - Powered by RSSHub",
      "errorAt": "2026-01-27T15:26:50.187Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "146868883707305984",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://xchar.app/nyyg",
      "title": "Crossbell Notes from 云野阁",
      "type": "feed",
      "url": "rsshub://crossbell/notes/character/73369"
    },
    {
      "description": "Crossbell Notes from 棒无 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "54887751043994624",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://xchar.app/bangwu",
      "title": "Crossbell Notes from 棒无",
      "type": "feed",
      "url": "rsshub://crossbell/notes/character/69522"
    }
  ],
  "url": "crossbell.io/*"
}
```
