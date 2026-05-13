# Raspberry Pi - Official Magazine

## Coverage
`index-only`

## Route
- Namespace: `raspberrypi`
- Namespace Name: `Raspberry Pi`
- Route Path: `/magazine`
- Route Name: `Official Magazine`
- Example: `/raspberrypi/magazine`
- URL: `magazine.raspberrypi.com`
- Language: `en`
- Categories: `programming`
- Maintainers: `nczitzk`
- Source Location: `magazine.ts`
- Source Module: `() => import('@/routes/raspberrypi/magazine.ts')`

## Description
_None_

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `magazine.raspberrypi.com`
- `target`: `/raspberrypi/magazine`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/raspberrypi/magazine",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "magazine.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/raspberrypi/magazine.ts')",
  "name": "Official Magazine",
  "path": "/magazine",
  "radar": [
    {
      "source": [
        "magazine.raspberrypi.com"
      ],
      "target": "/raspberrypi/magazine"
    }
  ],
  "url": "magazine.raspberrypi.com",
  "view": 0
}
```
