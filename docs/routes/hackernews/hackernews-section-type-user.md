# Hacker News - User

## Coverage
`index-only`

## Route
- Namespace: `hackernews`
- Namespace Name: `Hacker News`
- Route Path: `/hackernews/:section?/:type?/:user?`
- Route Name: `User`
- Example: `/hackernews/threads/comments_list/dang`
- URL: `ycombinator.com`
- Language: `_None_`
- Categories: `programming, popular`
- Maintainers: `nczitzk, xie-dongping`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
Subscribe to the content of a specific user

## Parameters
- `section`: {"description": "Content section, default to `index`"}
- `type`: {"description": "Link type, default to `sources`"}
- `user`: {"description": "Set user, only valid in `threads` and `submitted` sections"}


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
  - `news.ycombinator.com/:section`
  - `news.ycombinator.com/`

## Raw JSON
```json
{
  "categories": [
    "programming",
    "popular"
  ],
  "description": "Subscribe to the content of a specific user",
  "example": "/hackernews/threads/comments_list/dang",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 6607,
  "location": "index.ts",
  "maintainers": [
    "nczitzk",
    "xie-dongping"
  ],
  "name": "User",
  "parameters": {
    "section": {
      "description": "Content section, default to `index`"
    },
    "type": {
      "description": "Link type, default to `sources`"
    },
    "user": {
      "description": "Set user, only valid in `threads` and `submitted` sections"
    }
  },
  "path": "/:section?/:type?/:user?",
  "radar": [
    {
      "source": [
        "news.ycombinator.com/:section",
        "news.ycombinator.com/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Hacker News - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "52325519371718656",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://news.ycombinator.com/",
      "title": "Hacker News",
      "type": "feed",
      "url": "rsshub://hackernews"
    },
    {
      "description": "Hacker News - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "61780263784145920",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://news.ycombinator.com/",
      "title": "Hacker News",
      "type": "feed",
      "url": "rsshub://hackernews/index"
    }
  ],
  "view": 0
}
```
