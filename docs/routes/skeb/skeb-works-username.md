# Skeb - Creator Works

## Coverage
`index-only`

## Route
- Namespace: `skeb`
- Namespace Name: `Skeb`
- Route Path: `/skeb/works/:username`
- Route Name: `Creator Works`
- Example: `/skeb/works/@brm2_1925`
- URL: `skeb.jp`
- Language: `_None_`
- Categories: `picture`
- Maintainers: `SnowAgar25`
- Source Location: `works.ts`
- Source Module: `_None_`

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
  "heat": 2,
  "location": "works.ts",
  "maintainers": [
    "SnowAgar25"
  ],
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
  ],
  "topFeeds": [
    {
      "description": "Skeb - @2BV007's Works - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "192629445934388224",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://skeb.jp/@2BV007",
      "title": "Skeb - @2BV007's Works",
      "type": "feed",
      "url": "rsshub://skeb/works/@2BV007"
    }
  ]
}
```
