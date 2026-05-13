# CosplayTele - Popular

## Coverage
`index-only`

## Route
- Namespace: `cosplaytele`
- Namespace Name: `CosplayTele`
- Route Path: `/popular/:period`
- Route Name: `Popular`
- Example: `/cosplaytele/popular/3`
- URL: `cosplaytele.com/`
- Language: `en`
- Categories: `picture`
- Maintainers: `AiraNadih`
- Source Location: `popular.ts`
- Source Module: `() => import('@/routes/cosplaytele/popular.ts')`

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
  - `cosplaytele.com/:period`
- `target`: `/popular/:period`

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "example": "/cosplaytele/popular/3",
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
  "module": "() => import('@/routes/cosplaytele/popular.ts')",
  "name": "Popular",
  "parameters": {
    "period": "Days"
  },
  "path": "/popular/:period",
  "radar": [
    {
      "source": [
        "cosplaytele.com/:period"
      ],
      "target": "/popular/:period"
    }
  ],
  "url": "cosplaytele.com/"
}
```
