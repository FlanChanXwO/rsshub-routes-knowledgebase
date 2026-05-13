# GitKraken - Release Notes

## Coverage
`index-only`

## Route
- Namespace: `gitkraken`
- Namespace Name: `GitKraken`
- Route Path: `/release-note`
- Route Name: `Release Notes`
- Example: `/gitkraken/release-note`
- URL: `help.gitkraken.com/gitkraken-desktop/current/`
- Language: `_None_`
- Categories: `program-update`
- Maintainers: `TonyRL`
- Source Location: `release-note.ts`
- Source Module: `() => import('@/routes/gitkraken/release-note.ts')`

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
  - `help.gitkraken.com/gitkraken-desktop/current/`
### Rule 2
- `source`:
  - `www.gitkraken.com/`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "example": "/gitkraken/release-note",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "release-note.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/gitkraken/release-note.ts')",
  "name": "Release Notes",
  "path": "/release-note",
  "radar": [
    {
      "source": [
        "help.gitkraken.com/gitkraken-desktop/current/"
      ]
    },
    {
      "source": [
        "www.gitkraken.com/"
      ]
    }
  ],
  "url": "help.gitkraken.com/gitkraken-desktop/current/"
}
```
