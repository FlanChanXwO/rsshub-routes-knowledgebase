# WebCatalog - Changelog

## Coverage
`index-only`

## Route
- Namespace: `webcatalog`
- Namespace Name: `WebCatalog`
- Route Path: `/changelog`
- Route Name: `Changelog`
- Example: `/webcatalog/changelog`
- URL: `desktop.webcatalog.io/en/changelog`
- Language: `en`
- Categories: `program-update`
- Maintainers: `Tsuyumi25`
- Source Location: `changelog.ts`
- Source Module: `() => import('@/routes/webcatalog/changelog.ts')`

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
  - `desktop.webcatalog.io/:lang/changelog`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "example": "/webcatalog/changelog",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "changelog.ts",
  "maintainers": [
    "Tsuyumi25"
  ],
  "module": "() => import('@/routes/webcatalog/changelog.ts')",
  "name": "Changelog",
  "parameters": {},
  "path": "/changelog",
  "radar": [
    {
      "source": [
        "desktop.webcatalog.io/:lang/changelog"
      ]
    }
  ],
  "url": "desktop.webcatalog.io/en/changelog"
}
```
