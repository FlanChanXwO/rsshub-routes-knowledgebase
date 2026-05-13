# pixiv - Rankings

## Coverage
`index-only`

## Route
- Namespace: `pixiv`
- Namespace Name: `pixiv`
- Route Path: `/ranking/:mode/:date?`
- Route Name: `Rankings`
- Example: `/pixiv/ranking/week`
- URL: `www.pixiv.net`
- Language: `ja`
- Categories: `social-media`
- Maintainers: `EYHN`
- Source Location: `ranking.ts`
- Source Module: `() => import('@/routes/pixiv/ranking.ts')`

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
    "social-media"
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
  "location": "ranking.ts",
  "maintainers": [
    "EYHN"
  ],
  "module": "() => import('@/routes/pixiv/ranking.ts')",
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
  "view": 2
}
```
