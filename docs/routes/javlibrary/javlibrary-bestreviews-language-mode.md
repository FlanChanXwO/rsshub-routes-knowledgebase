# JAVLibrary - Best Reviews

## Coverage
`index-only`

## Route
- Namespace: `javlibrary`
- Namespace Name: `JAVLibrary`
- Route Path: `/javlibrary/bestreviews/:language?/:mode?`
- Route Name: `Best Reviews`
- Example: `/javlibrary/bestreviews/en`
- URL: `javlibrary.com`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `nczitzk`
- Source Location: `bestreviews.ts`
- Source Module: `_None_`

## Description
| Last Month | All Time |
| ---------- | -------- |
| 1          | 2        |

## Parameters
- `language`: Language, see below, Japanese by default, as `ja`
- `mode`: Mode, see below, Last Month by default, as `1`


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "description": "| Last Month | All Time |\n| ---------- | -------- |\n| 1          | 2        |",
  "example": "/javlibrary/bestreviews/en",
  "features": {
    "antiCrawler": true,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 79,
  "location": "bestreviews.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Best Reviews",
  "parameters": {
    "language": "Language, see below, Japanese by default, as `ja`",
    "mode": "Mode, see below, Last Month by default, as `1`"
  },
  "path": "/bestreviews/:language?/:mode?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": null,
      "errorAt": "2025-06-08T19:57:05.819Z",
      "errorMessage": "[GET] \"https://www.javlibrary.com/ja/tl_bestreviews.php?list&mode=1\": 403 Forbidden\n",
      "id": "154611732345126913",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://javlibrary/bestreviews"
    },
    {
      "description": null,
      "errorAt": "2025-07-28T06:23:29.873Z",
      "errorMessage": "[GET] \"https://www.javlibrary.com/zh/tl_bestreviews.php?list&mode=2\": 403 Forbidden\n",
      "id": "172541899423889409",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://javlibrary/bestreviews/zh/2"
    }
  ]
}
```
