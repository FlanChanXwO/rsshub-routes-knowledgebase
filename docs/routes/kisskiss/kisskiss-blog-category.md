# KISS - ブログ

## Coverage
`index-only`

## Route
- Namespace: `kisskiss`
- Namespace Name: `KISS`
- Route Path: `/kisskiss/blog/:category?`
- Route Name: `ブログ`
- Example: `/blog/DLC`
- URL: `www.kisskiss.tv`
- Language: `_None_`
- Categories: `game`
- Maintainers: `keocheung`
- Source Location: `blog.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `category`: category


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `www.kisskiss.tv/kiss/diary.php`
- `target`: `/blog`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "example": "/blog/DLC",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "blog.ts",
  "maintainers": [
    "keocheung"
  ],
  "name": "ブログ",
  "parameters": {
    "category": "category"
  },
  "path": "/blog/:category?",
  "radar": [
    {
      "source": [
        "www.kisskiss.tv/kiss/diary.php"
      ],
      "target": "/blog"
    }
  ],
  "topFeeds": [
    {
      "description": "KISS ブログ - Powered by RSSHub",
      "errorAt": "2025-12-09T20:19:56.802Z",
      "errorMessage": "Cannot read properties of null (reading '0')\n",
      "id": "65292416725202944",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.kisskiss.tv/kiss/diary.php?category=DLC",
      "title": "KISS ブログ",
      "type": "feed",
      "url": "rsshub://kisskiss/blog/DLC"
    }
  ]
}
```
