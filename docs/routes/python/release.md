# Python - Active Python Releases

## Coverage
`index-only`

## Route
- Namespace: `python`
- Namespace Name: `Python`
- Route Path: `/release`
- Route Name: `Active Python Releases`
- Example: `/python/release`
- URL: `www.python.org`
- Language: `en`
- Categories: `programming`
- Maintainers: `nczitzk`
- Source Location: `release.ts`
- Source Module: `() => import('@/routes/python/release.ts')`

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
  - `www.python.org`
  - `www.python.org/downloads`
- `target`: `/release`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/python/release",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "release.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/python/release.ts')",
  "name": "Active Python Releases",
  "path": "/release",
  "radar": [
    {
      "source": [
        "www.python.org",
        "www.python.org/downloads"
      ],
      "target": "/release"
    }
  ],
  "url": "www.python.org",
  "view": 0
}
```
