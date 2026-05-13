# Kiro - Changelog

## Coverage
`index-only`

## Route
- Namespace: `kiro`
- Namespace Name: `Kiro`
- Route Path: `/changelog`
- Route Name: `Changelog`
- Example: `/kiro/changelog`
- URL: `kiro.dev`
- Language: `en`
- Categories: `program-update`
- Maintainers: `nczitzk`
- Source Location: `changelog.ts`
- Source Module: `() => import('@/routes/kiro/changelog.ts')`

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
  - `kiro.dev`
  - `kiro.dev/changelog/`
- `target`: `/changelog`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "example": "/kiro/changelog",
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
  "module": "() => import('@/routes/kiro/changelog.ts')",
  "name": "Changelog",
  "path": "/changelog",
  "radar": [
    {
      "source": [
        "kiro.dev",
        "kiro.dev/changelog/"
      ],
      "target": "/changelog"
    }
  ],
  "url": "kiro.dev",
  "view": 0
}
```
