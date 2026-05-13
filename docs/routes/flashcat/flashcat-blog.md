# Flashcat - 快猫星云博客

## Coverage
`index-only`

## Route
- Namespace: `flashcat`
- Namespace Name: `Flashcat`
- Route Path: `/flashcat/blog`
- Route Name: `快猫星云博客`
- Example: `/flashcat/blog`
- URL: `flashcat.cloud`
- Language: `_None_`
- Categories: `blog`
- Maintainers: `chesha1`
- Source Location: `blog.ts`
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
  - `flashcat.cloud/blog`
- `target`: `/blog`

## Raw JSON
```json
{
  "categories": [
    "blog"
  ],
  "example": "/flashcat/blog",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 29,
  "location": "blog.ts",
  "maintainers": [
    "chesha1"
  ],
  "name": "快猫星云博客",
  "parameters": {},
  "path": "/blog",
  "radar": [
    {
      "source": [
        "flashcat.cloud/blog"
      ],
      "target": "/blog"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Flashcat 快猫星云博客 - Powered by RSSHub",
      "errorAt": "2026-04-12T16:17:28.026Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\nthis route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "58629995296859136",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://flashcat.cloud/blog/",
      "title": "Flashcat 快猫星云博客",
      "type": "feed",
      "url": "rsshub://flashcat/blog"
    }
  ]
}
```
