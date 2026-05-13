# 4KUP - Popular

## Coverage
`index-only`

## Route
- Namespace: `4kup`
- Namespace Name: `4KUP`
- Route Path: `/popular/:period`
- Route Name: `Popular`
- Example: `/4kup/popular/7`
- URL: `4kup.net/`
- Language: `en`
- Categories: `picture`
- Maintainers: `AiraNadih`
- Source Location: `popular.ts`
- Source Module: `() => import('@/routes/4kup/popular.ts')`

## Description
_None_

## Parameters
- `period`: Days


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
  - `4kup.net/:period`
- `target`: `/popular/:period`

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "example": "/4kup/popular/7",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "popular.ts",
  "maintainers": [
    "AiraNadih"
  ],
  "module": "() => import('@/routes/4kup/popular.ts')",
  "name": "Popular",
  "parameters": {
    "period": "Days"
  },
  "path": "/popular/:period",
  "radar": [
    {
      "source": [
        "4kup.net/:period"
      ],
      "target": "/popular/:period"
    }
  ],
  "url": "4kup.net/"
}
```
