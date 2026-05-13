# カドコミ(Kadocomi) - 漫画详情

## Coverage
`index-only`

## Route
- Namespace: `comic-walker`
- Namespace Name: `カドコミ(Kadocomi)`
- Route Path: `/comic-walker/manga/:id`
- Route Name: `漫画详情`
- Example: `/comic-walker/manga/KC_006778_S`
- URL: `comic-walker.com`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `xiaobailoves`
- Source Location: `manga.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: カドコミ(Kadocomi)中对应的作品workCode，例如 KC_006778_S


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
  - `comic-walker.com/detail/:id`
- `target`: `/manga/:id`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "example": "/comic-walker/manga/KC_006778_S",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "manga.ts",
  "maintainers": [
    "xiaobailoves"
  ],
  "name": "漫画详情",
  "parameters": {
    "id": "カドコミ(Kadocomi)中对应的作品workCode，例如 KC_006778_S"
  },
  "path": "/manga/:id",
  "radar": [
    {
      "source": [
        "comic-walker.com/detail/:id"
      ],
      "target": "/manga/:id"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected -434069720 to be greater than -432000000\n    at checkDate (/home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:37:46)\n    at checkRSS (/home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:63:13)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:82:17\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
