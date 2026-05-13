# Bandcamp - Upcoming Live Streams

## Coverage
`index-only`

## Route
- Namespace: `bandcamp`
- Namespace Name: `Bandcamp`
- Route Path: `/live`
- Route Name: `Upcoming Live Streams`
- Example: `/bandcamp/live`
- URL: `bandcamp.com/live_schedule`
- Language: `en`
- Categories: `multimedia`
- Maintainers: `nczitzk`
- Source Location: `live.ts`
- Source Module: `() => import('@/routes/bandcamp/live.ts')`

## Description
_None_

## Parameters
_None_


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
  - `bandcamp.com/live_schedule`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/bandcamp/live",
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
    "nczitzk"
  ],
  "module": "() => import('@/routes/bandcamp/live.ts')",
  "name": "Upcoming Live Streams",
  "parameters": {},
  "path": "/live",
  "radar": [
    {
      "source": [
        "bandcamp.com/live_schedule"
      ]
    }
  ],
  "url": "bandcamp.com/live_schedule"
}
```
