# TapTap - Game's Changelog

## Coverage
`index-only`

## Route
- Namespace: `taptap`
- Namespace Name: `TapTap`
- Route Path: `/intl/changelog/:id/:lang?`
- Route Name: `Game's Changelog`
- Example: `/taptap/intl/changelog/191001/zh_TW`
- URL: `www.taptap.io`
- Language: `zh-CN`
- Categories: `game`
- Maintainers: `hoilc, ETiV`
- Source Location: `changelog-intl.ts`
- Source Module: `() => import('@/routes/taptap/changelog-intl.ts')`

## Description
Language Code

| English (US) | 繁體中文 | 한국어 | 日本語 |
| ------------ | -------- | ------ | ------ |
| en_US       | zh_TW   | ko_KR | ja_JP |

## Parameters
- `id`: Game's App ID, you may find it from the URL of the Game
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
  - `www.taptap.io/app/:id`
- `target`: `/intl/changelog/:id`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "Language Code\n\n| English (US) | 繁體中文 | 한국어 | 日本語 |\n| ------------ | -------- | ------ | ------ |\n| en_US       | zh_TW   | ko_KR | ja_JP |",
  "example": "/taptap/intl/changelog/191001/zh_TW",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "changelog-intl.ts",
  "maintainers": [
    "hoilc",
    "ETiV"
  ],
  "module": "() => import('@/routes/taptap/changelog-intl.ts')",
  "name": "Game's Changelog",
  "parameters": {
    "id": "Game's App ID, you may find it from the URL of the Game",
    "lang": "Language, checkout the table below for possible values, default is `en_US`"
  },
  "path": "/intl/changelog/:id/:lang?",
  "radar": [
    {
      "source": [
        "www.taptap.io/app/:id"
      ],
      "target": "/intl/changelog/:id"
    }
  ]
}
```
