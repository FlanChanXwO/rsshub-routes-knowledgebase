# Cursor - Changelog

## Coverage
`index-only`

## Route
- Namespace: `cursor`
- Namespace Name: `Cursor`
- Route Path: `/changelog/:locale?`
- Route Name: `Changelog`
- Example: `/cursor/changelog`
- URL: `cursor.com`
- Language: `en`
- Categories: `program-update`
- Maintainers: `p3psi-boo, nczitzk`
- Source Location: `changelog.ts`
- Source Module: `() => import('@/routes/cursor/changelog.ts')`

## Description
_None_

## Parameters
- `locale`: Locale appended to the route path, e.g. `ja`


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
  - `cursor.com/changelog`
- `target`: `/changelog`
### Rule 2
- `source`:
  - `cursor.com/:locale/changelog`
- `target`: `/changelog/:locale`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "example": "/cursor/changelog",
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
    "p3psi-boo",
    "nczitzk"
  ],
  "module": "() => import('@/routes/cursor/changelog.ts')",
  "name": "Changelog",
  "parameters": {
    "locale": "Locale appended to the route path, e.g. `ja`"
  },
  "path": "/changelog/:locale?",
  "radar": [
    {
      "source": [
        "cursor.com/changelog"
      ],
      "target": "/changelog"
    },
    {
      "source": [
        "cursor.com/:locale/changelog"
      ],
      "target": "/changelog/:locale"
    }
  ],
  "url": "cursor.com",
  "view": 0
}
```
