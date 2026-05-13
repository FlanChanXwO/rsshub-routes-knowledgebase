# TapTap - Ratings & Reviews

## Coverage
`index-only`

## Route
- Namespace: `taptap`
- Namespace Name: `TapTap`
- Route Path: `/intl/review/:id/:order?/:lang?`
- Route Name: `Ratings & Reviews`
- Example: `/taptap/intl/review/82354/recent`
- URL: `www.taptap.io`
- Language: `zh-CN`
- Categories: `game`
- Maintainers: `hoilc, TonyRL, ETiV`
- Source Location: `review-intl.ts`
- Source Module: `() => import('@/routes/taptap/review-intl.ts')`

## Description
Sort Method

| Most Helpful | Most Recent |
| ------------ | ----------- |
| helpful      | recent      |

Language Code

| English (US) | 繁體中文 | 한국어 | 日本語 |
| ------------ | -------- | ------ | ------ |
| en_US       | zh_TW   | ko_KR | ja_JP |

## Parameters
- `id`: Game's App ID, you may find it from the URL of the Game
- `order`: Sort Method, default is `helpful`, checkout the table below for possible values
- `lang`: Language, checkout the table below for possible values, default is `en_US`


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
  - `www.taptap.io/app/:id/review`
  - `www.taptap.io/app/:id`
- `target`: `/intl/review/:id`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "Sort Method\n\n| Most Helpful | Most Recent |\n| ------------ | ----------- |\n| helpful      | recent      |\n\nLanguage Code\n\n| English (US) | 繁體中文 | 한국어 | 日本語 |\n| ------------ | -------- | ------ | ------ |\n| en_US       | zh_TW   | ko_KR | ja_JP |",
  "example": "/taptap/intl/review/82354/recent",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "review-intl.ts",
  "maintainers": [
    "hoilc",
    "TonyRL",
    "ETiV"
  ],
  "module": "() => import('@/routes/taptap/review-intl.ts')",
  "name": "Ratings & Reviews",
  "parameters": {
    "id": "Game's App ID, you may find it from the URL of the Game",
    "lang": "Language, checkout the table below for possible values, default is `en_US`",
    "order": "Sort Method, default is `helpful`, checkout the table below for possible values"
  },
  "path": "/intl/review/:id/:order?/:lang?",
  "radar": [
    {
      "source": [
        "www.taptap.io/app/:id/review",
        "www.taptap.io/app/:id"
      ],
      "target": "/intl/review/:id"
    }
  ]
}
```
