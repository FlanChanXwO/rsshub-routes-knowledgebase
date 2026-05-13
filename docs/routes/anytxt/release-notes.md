# Anytxt Searcher - Release Notes

## Coverage
`index-only`

## Route
- Namespace: `anytxt`
- Namespace Name: `Anytxt Searcher`
- Route Path: `/release-notes`
- Route Name: `Release Notes`
- Example: `/anytxt/release-notes`
- URL: `anytxt.net`
- Language: `zh-CN`
- Categories: `program-update`
- Maintainers: `nczitzk`
- Source Location: `release-notes.ts`
- Source Module: `() => import('@/routes/anytxt/release-notes.ts')`

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
  - `anytxt.net`
- `target`: `/anytxt/release-notes`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "example": "/anytxt/release-notes",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "release-notes.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/anytxt/release-notes.ts')",
  "name": "Release Notes",
  "path": "/release-notes",
  "radar": [
    {
      "source": [
        "anytxt.net"
      ],
      "target": "/anytxt/release-notes"
    }
  ],
  "url": "anytxt.net",
  "view": 0
}
```
