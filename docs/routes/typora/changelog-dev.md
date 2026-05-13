# Typora - Dev Release Changelog

## Coverage
`index-only`

## Route
- Namespace: `typora`
- Namespace Name: `Typora`
- Route Path: `/changelog/dev`
- Route Name: `Dev Release Changelog`
- Example: `/typora/changelog/dev`
- URL: `support.typora.io/`
- Language: `en`
- Categories: `program-update`
- Maintainers: `nczitzk`
- Source Location: `changelog-dev.ts`
- Source Module: `() => import('@/routes/typora/changelog-dev.ts')`

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
  - `support.typora.io/`
- `target`: `/changelog`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "example": "/typora/changelog/dev",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "changelog-dev.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/typora/changelog-dev.ts')",
  "name": "Dev Release Changelog",
  "parameters": {},
  "path": "/changelog/dev",
  "radar": [
    {
      "source": [
        "support.typora.io/"
      ],
      "target": "/changelog"
    }
  ],
  "url": "support.typora.io/"
}
```
