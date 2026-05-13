# Galxe - Quest

## Coverage
`index-only`

## Route
- Namespace: `galxe`
- Namespace Name: `Galxe`
- Route Path: `/quest/:alias`
- Route Name: `Quest`
- Example: `/galxe/quest/MissionWeb3`
- URL: `app.galxe.com`
- Language: `zh-CN`
- Categories: `other`
- Maintainers: `cxheng315`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/galxe/index.ts')`

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
  - `app.galxe.com/quest/:alias`
- `target`: `/quest/:alias`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "example": "/galxe/quest/MissionWeb3",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.ts",
  "maintainers": [
    "cxheng315"
  ],
  "module": "() => import('@/routes/galxe/index.ts')",
  "name": "Quest",
  "path": "/quest/:alias",
  "radar": [
    {
      "source": [
        "app.galxe.com/quest/:alias"
      ],
      "target": "/quest/:alias"
    }
  ],
  "url": "app.galxe.com"
}
```
