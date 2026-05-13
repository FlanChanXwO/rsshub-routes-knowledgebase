# Skeb - Following Works

## Coverage
`index-only`

## Route
- Namespace: `skeb`
- Namespace Name: `Skeb`
- Route Path: `/following_works/:username`
- Route Name: `Following Works`
- Example: `/skeb/following_works/@brm2_1925`
- URL: `skeb.jp`
- Language: `ja`
- Categories: `picture`
- Maintainers: `SnowAgar25`
- Source Location: `following-works.ts`
- Source Module: `() => import('@/routes/skeb/following-works.ts')`

## Description
Get the latest works for the specified user's followings on Skeb.

## Parameters
- `username`: Skeb Username with @


## Features
- `requireConfig`: [{"description": "在瀏覽器開發者工具（F12）的主控台中輸入 `localStorage.getItem(\"token\")` 獲取", "name": "SKEB_BEARER_TOKEN", "optional": false}]
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
### Rule 1
- `title`: `Following Works`
- `source`:
  - `skeb.jp/:username`
- `target`: `/following_works/:username`

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "description": "Get the latest works for the specified user's followings on Skeb.",
  "example": "/skeb/following_works/@brm2_1925",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": [
      {
        "description": "在瀏覽器開發者工具（F12）的主控台中輸入 `localStorage.getItem(\"token\")` 獲取",
        "name": "SKEB_BEARER_TOKEN",
        "optional": false
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "following-works.ts",
  "maintainers": [
    "SnowAgar25"
  ],
  "module": "() => import('@/routes/skeb/following-works.ts')",
  "name": "Following Works",
  "parameters": {
    "username": "Skeb Username with @"
  },
  "path": "/following_works/:username",
  "radar": [
    {
      "source": [
        "skeb.jp/:username"
      ],
      "target": "/following_works/:username",
      "title": "Following Works"
    }
  ]
}
```
