# Skeb - Creator Works

## Coverage
`index-only`

## Route
- Namespace: `skeb`
- Namespace Name: `Skeb`
- Route Path: `/works/:username`
- Route Name: `Creator Works`
- Example: `/skeb/works/@brm2_1925`
- URL: `skeb.jp`
- Language: `ja`
- Categories: `picture`
- Maintainers: `SnowAgar25`
- Source Location: `works.ts`
- Source Module: `() => import('@/routes/skeb/works.ts')`

## Description
Get the latest works of a specific creator on Skeb

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
- `title`: `Creator Works`
- `source`:
  - `skeb.jp/:username`
- `target`: `/works/:username`

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "description": "Get the latest works of a specific creator on Skeb",
  "example": "/skeb/works/@brm2_1925",
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
  "location": "works.ts",
  "maintainers": [
    "SnowAgar25"
  ],
  "module": "() => import('@/routes/skeb/works.ts')",
  "name": "Creator Works",
  "parameters": {
    "username": "Skeb Username with @"
  },
  "path": "/works/:username",
  "radar": [
    {
      "source": [
        "skeb.jp/:username"
      ],
      "target": "/works/:username",
      "title": "Creator Works"
    }
  ]
}
```
