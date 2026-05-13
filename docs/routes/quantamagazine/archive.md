# Quanta Magazine - Archive

## Coverage
`index-only`

## Route
- Namespace: `quantamagazine`
- Namespace Name: `Quanta Magazine`
- Route Path: `/archive`
- Route Name: `Archive`
- Example: `/quantamagazine/archive`
- URL: `quantamagazine.org`
- Language: `en`
- Categories: `new-media`
- Maintainers: `emdoe`
- Source Location: `archive.ts`
- Source Module: `() => import('@/routes/quantamagazine/archive.ts')`

## Description
Get the latest articles from Quanta Magazine.

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
  - `quantamagazine.org`
- `target`: `/archive`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "Get the latest articles from Quanta Magazine.",
  "example": "/quantamagazine/archive",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "archive.ts",
  "maintainers": [
    "emdoe"
  ],
  "module": "() => import('@/routes/quantamagazine/archive.ts')",
  "name": "Archive",
  "parameters": {},
  "path": "/archive",
  "radar": [
    {
      "source": [
        "quantamagazine.org"
      ],
      "target": "/archive"
    }
  ],
  "url": "quantamagazine.org"
}
```
