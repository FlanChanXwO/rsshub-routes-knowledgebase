# Skeb - Following Creators

## Coverage
`index-only`

## Route
- Namespace: `skeb`
- Namespace Name: `Skeb`
- Route Path: `/following_creators/:username`
- Route Name: `Following Creators`
- Example: `/skeb/following_creators/@brm2_1925`
- URL: `skeb.jp`
- Language: `ja`
- Categories: `picture`
- Maintainers: `SnowAgar25`
- Source Location: `following-creators.ts`
- Source Module: `() => import('@/routes/skeb/following-creators.ts')`

## Description
Get the list of creators the specified user is following on Skeb.

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
- `title`: `Following Creators`
- `source`:
  - `skeb.jp/:username`
- `target`: `/following_creators/:username`

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "description": "Get the list of creators the specified user is following on Skeb.",
  "example": "/skeb/following_creators/@brm2_1925",
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
  "location": "following-creators.ts",
  "maintainers": [
    "SnowAgar25"
  ],
  "module": "() => import('@/routes/skeb/following-creators.ts')",
  "name": "Following Creators",
  "parameters": {
    "username": "Skeb Username with @"
  },
  "path": "/following_creators/:username",
  "radar": [
    {
      "source": [
        "skeb.jp/:username"
      ],
      "target": "/following_creators/:username",
      "title": "Following Creators"
    }
  ]
}
```
