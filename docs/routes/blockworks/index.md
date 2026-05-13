# Blockworks - News

## Coverage
`index-only`

## Route
- Namespace: `blockworks`
- Namespace Name: `Blockworks`
- Route Path: `/`
- Route Name: `News`
- Example: `/blockworks`
- URL: `blockworks.co`
- Language: `en`
- Categories: `finance`
- Maintainers: `pseudoyu`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/blockworks/index.ts')`

## Description
Blockworks news with full text support.

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
  - `blockworks.co/`
- `target`: `/`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "description": "Blockworks news with full text support.",
  "example": "/blockworks",
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
    "pseudoyu"
  ],
  "module": "() => import('@/routes/blockworks/index.ts')",
  "name": "News",
  "parameters": {},
  "path": "/",
  "radar": [
    {
      "source": [
        "blockworks.co/"
      ],
      "target": "/"
    }
  ]
}
```
