# Dribbble - Keyword

## Coverage
`index-only`

## Route
- Namespace: `dribbble`
- Namespace Name: `Dribbble`
- Route Path: `/dribbble/keyword/:keyword`
- Route Name: `Keyword`
- Example: `/dribbble/keyword/player`
- URL: `dribbble.com`
- Language: `_None_`
- Categories: `design`
- Maintainers: `DIYgod, loganrockmore`
- Source Location: `keyword.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `keyword`: desired keyword


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
    "design"
  ],
  "example": "/dribbble/keyword/player",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 28,
  "location": "keyword.ts",
  "maintainers": [
    "DIYgod",
    "loganrockmore"
  ],
  "name": "Keyword",
  "parameters": {
    "keyword": "desired keyword"
  },
  "path": "/keyword/:keyword",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "Explore thousands of high-quality player images on Dribbble. Your resource to get inspired, discover and connect with designers worldwide. - Powered by RSSHub",
      "errorAt": "2025-05-30T16:24:34.174Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\nthis route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "71093465085819904",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://dribbble.com/search/shots/recent?q=player",
      "title": "Dribbble - keyword player",
      "type": "feed",
      "url": "rsshub://dribbble/keyword/player"
    },
    {
      "description": "Explore thousands of high-quality brand design images on Dribbble. Your resource to get inspired, discover and connect with designers worldwide. - Powered by RSSHub",
      "errorAt": "2025-05-30T15:54:35.008Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "82797353618561024",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://dribbble.com/search/shots/recent?q=brand%20design",
      "title": "Dribbble - keyword brand design",
      "type": "feed",
      "url": "rsshub://dribbble/keyword/brand%20design"
    }
  ]
}
```
