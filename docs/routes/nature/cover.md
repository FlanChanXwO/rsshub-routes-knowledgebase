# Nature Journal - Cover Story

## Coverage
`index-only`

## Route
- Namespace: `nature`
- Namespace Name: `Nature Journal`
- Route Path: `/cover`
- Route Name: `Cover Story`
- Example: `/nature/cover`
- URL: `nature.com/`
- Language: `en`
- Categories: `journal`
- Maintainers: `y9c, pseudoyu`
- Source Location: `cover.ts`
- Source Module: `() => import('@/routes/nature/cover.ts')`

## Description
Subscribe to the cover images of the Nature journals, and get the latest publication updates in time.

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
  - `nature.com/`

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "description": "Subscribe to the cover images of the Nature journals, and get the latest publication updates in time.",
  "example": "/nature/cover",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "cover.ts",
  "maintainers": [
    "y9c",
    "pseudoyu"
  ],
  "module": "() => import('@/routes/nature/cover.ts')",
  "name": "Cover Story",
  "parameters": {},
  "path": "/cover",
  "radar": [
    {
      "source": [
        "nature.com/"
      ]
    }
  ],
  "url": "nature.com/"
}
```
