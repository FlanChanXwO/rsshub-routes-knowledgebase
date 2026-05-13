# Postman - Release Notes

## Coverage
`index-only`

## Route
- Namespace: `postman`
- Namespace Name: `Postman`
- Route Path: `/release-notes`
- Route Name: `Release Notes`
- Example: `/postman/release-notes`
- URL: `postman.com/downloads/release-notes`
- Language: `en`
- Categories: `program-update`
- Maintainers: `nczitzk`
- Source Location: `release-notes.ts`
- Source Module: `() => import('@/routes/postman/release-notes.ts')`

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
  - `postman.com/downloads/release-notes`
  - `postman.com/`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "example": "/postman/release-notes",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "release-notes.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/postman/release-notes.ts')",
  "name": "Release Notes",
  "parameters": {},
  "path": "/release-notes",
  "radar": [
    {
      "source": [
        "postman.com/downloads/release-notes",
        "postman.com/"
      ]
    }
  ],
  "url": "postman.com/downloads/release-notes"
}
```
