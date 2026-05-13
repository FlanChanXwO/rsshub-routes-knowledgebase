# TikTok - Live

## Coverage
`index-only`

## Route
- Namespace: `tiktok`
- Namespace Name: `TikTok`
- Route Path: `/live/:user`
- Route Name: `Live`
- Example: `/tiktok/live/@shinichifuku`
- URL: `tiktok.com`
- Language: `en`
- Categories: `social-media`
- Maintainers: `TonyRL`
- Source Location: `live.ts`
- Source Module: `() => import('@/routes/tiktok/live.ts')`

## Description
_None_

## Parameters
- `user`: User ID, including @


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
  - `www.tiktok.com/:user/live`
- `target`: `/live/:user`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/tiktok/live/@shinichifuku",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "live.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/tiktok/live.ts')",
  "name": "Live",
  "parameters": {
    "user": "User ID, including @"
  },
  "path": "/live/:user",
  "radar": [
    {
      "source": [
        "www.tiktok.com/:user/live"
      ],
      "target": "/live/:user"
    }
  ]
}
```
