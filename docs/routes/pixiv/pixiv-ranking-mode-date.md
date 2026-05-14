# pixiv - Rankings

## Coverage
`index-only`

## Route
- Namespace: `pixiv`
- Namespace Name: `pixiv`
- Route Path: `/pixiv/ranking/:mode/:date?`
- Route Name: `Rankings`
- Example: `/pixiv/ranking/week`
- URL: `www.pixiv.net`
- Language: `_None_`
- Categories: `social-media, popular`
- Maintainers: `EYHN`
- Source Location: `ranking.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `mode`: {"default": "day", "description": "rank type", "options": [{"label": "daily rank", "value": "day"}, {"label": "weekly rank", "value": "week"}, {"label": "monthly rank", "value": "month"}, {"label": "male rank", "value": "day_male"}, {"label": "female rank", "value": "day_felame"}, {"label": "AI-generated work Rankings", "value": "day_ai"}, {"label": "original rank", "value": "week_original"}, {"label": "rookie user rank", "value": "week_rookie"}, {"label": "R-18 daily rank", "value": "day_r18"}, {"label": "R-18 AI-generated work", "value": "day_r18_ai"}, {"label": "R-18 male rank", "value": "day_male_r18"}, {"label": "R-18 female rank", "value": "day_female_r18"}, {"label": "R-18 weekly rank", "value": "week_r18"}, {"label": "R-18G rank", "value": "week_r18g"}]}
- `date`: format: `2018-4-25`


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
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
    "social-media",
    "popular"
  ],
  "example": "/pixiv/ranking/week",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 7684,
  "location": "ranking.ts",
  "maintainers": [
    "EYHN"
  ],
  "name": "Rankings",
  "parameters": {
    "date": "format: `2018-4-25`",
    "mode": {
      "default": "day",
      "description": "rank type",
      "options": [
        {
          "label": "daily rank",
          "value": "day"
        },
        {
          "label": "weekly rank",
          "value": "week"
        },
        {
          "label": "monthly rank",
          "value": "month"
        },
        {
          "label": "male rank",
          "value": "day_male"
        },
        {
          "label": "female rank",
          "value": "day_felame"
        },
        {
          "label": "AI-generated work Rankings",
          "value": "day_ai"
        },
        {
          "label": "original rank",
          "value": "week_original"
        },
        {
          "label": "rookie user rank",
          "value": "week_rookie"
        },
        {
          "label": "R-18 daily rank",
          "value": "day_r18"
        },
        {
          "label": "R-18 AI-generated work",
          "value": "day_r18_ai"
        },
        {
          "label": "R-18 male rank",
          "value": "day_male_r18"
        },
        {
          "label": "R-18 female rank",
          "value": "day_female_r18"
        },
        {
          "label": "R-18 weekly rank",
          "value": "week_r18"
        },
        {
          "label": "R-18G rank",
          "value": "week_r18g"
        }
      ]
    }
  },
  "path": "/ranking/:mode/:date?",
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "2026年5月13日 pixiv 日排行 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41427688948323328",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.pixiv.net/ranking.php?mode=daily",
      "title": "pixiv 日排行",
      "type": "feed",
      "url": "rsshub://pixiv/ranking/day"
    },
    {
      "description": "2026年5月13日 pixiv 周排行 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "41147805276726317",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.pixiv.net/ranking.php?mode=weekly",
      "title": "pixiv 周排行",
      "type": "feed",
      "url": "rsshub://pixiv/ranking/week"
    }
  ],
  "view": 2
}
```
