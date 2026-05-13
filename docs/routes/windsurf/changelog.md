# Windsurf - Changelog

## Coverage
`index-only`

## Route
- Namespace: `windsurf`
- Namespace Name: `Windsurf`
- Route Path: `/changelog`
- Route Name: `Changelog`
- Example: `/windsurf/changelog`
- URL: `windsurf.com`
- Language: `en`
- Categories: `programming`
- Maintainers: `nczitzk`
- Source Location: `changelog.ts`
- Source Module: `() => import('@/routes/windsurf/changelog.ts')`

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
  - `windsurf.com/changelog`
- `target`: `/changelog`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/windsurf/changelog",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "changelog.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/windsurf/changelog.ts')",
  "name": "Changelog",
  "path": "/changelog",
  "radar": [
    {
      "source": [
        "windsurf.com/changelog"
      ],
      "target": "/changelog"
    }
  ],
  "url": "windsurf.com",
  "view": 0
}
```
