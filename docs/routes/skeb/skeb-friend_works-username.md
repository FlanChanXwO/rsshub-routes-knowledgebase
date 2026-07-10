# Skeb - Friend Works

## Coverage
`index-only`

## Route
- Namespace: `skeb`
- Namespace Name: `Skeb`
- Route Path: `/skeb/friend_works/:username`
- Route Name: `Friend Works`
- Example: `/skeb/friend_works/@brm2_1925`
- URL: `skeb.jp`
- Language: `_None_`
- Categories: `picture`
- Maintainers: `SnowAgar25`
- Source Location: `friend-works.ts`
- Source Module: `_None_`

## Description
Get the latest requests for the specified user's followings on Skeb.

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
- `title`: `Friend Works`
- `source`:
  - `skeb.jp/:username`
- `target`: `/friend_works/:username`

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "description": "Get the latest requests for the specified user's followings on Skeb.",
  "example": "/skeb/friend_works/@brm2_1925",
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
  "heat": 0,
  "location": "friend-works.ts",
  "maintainers": [
    "SnowAgar25"
  ],
  "name": "Friend Works",
  "parameters": {
    "username": "Skeb Username with @"
  },
  "path": "/friend_works/:username",
  "radar": [
    {
      "source": [
        "skeb.jp/:username"
      ],
      "target": "/friend_works/:username",
      "title": "Friend Works"
    }
  ],
  "topFeeds": []
}
```
