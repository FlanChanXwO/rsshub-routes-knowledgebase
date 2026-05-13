# KISS - ブログ

## Coverage
`index-only`

## Route
- Namespace: `kisskiss`
- Namespace Name: `KISS`
- Route Path: `/blog/:category?`
- Route Name: `ブログ`
- Example: `/blog/DLC`
- URL: `www.kisskiss.tv`
- Language: `ja`
- Categories: `game`
- Maintainers: `keocheung`
- Source Location: `blog.ts`
- Source Module: `() => import('@/routes/kisskiss/blog.ts')`

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
  "location": "blog.ts",
  "maintainers": [
    "keocheung"
  ],
  "module": "() => import('@/routes/kisskiss/blog.ts')",
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
  ]
}
```
