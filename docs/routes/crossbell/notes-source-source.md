# Crossbell - Notes of source

## Coverage
`index-only`

## Route
- Namespace: `crossbell`
- Namespace Name: `Crossbell`
- Route Path: `/notes/source/:source`
- Route Name: `Notes of source`
- Example: `/crossbell/notes/source/xlog`
- URL: `crossbell.io/*`
- Language: `en`
- Categories: `social-media`
- Maintainers: `DIYgod`
- Source Location: `notes/source.ts`
- Source Module: `() => import('@/routes/crossbell/notes/source.ts')`

## Description
_None_

## Parameters
- `source`: N


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
  - `crossbell.io/*`
- `target`: `/notes`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/crossbell/notes/source/xlog",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "notes/source.ts",
  "maintainers": [
    "DIYgod"
  ],
  "module": "() => import('@/routes/crossbell/notes/source.ts')",
  "name": "Notes of source",
  "parameters": {
    "source": "N"
  },
  "path": "/notes/source/:source",
  "radar": [
    {
      "source": [
        "crossbell.io/*"
      ],
      "target": "/notes"
    }
  ],
  "url": "crossbell.io/*"
}
```
