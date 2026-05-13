# Zotero - Version History

## Coverage
`index-only`

## Route
- Namespace: `zotero`
- Namespace Name: `Zotero`
- Route Path: `/versions`
- Route Name: `Version History`
- Example: `/zotero/versions`
- URL: `zotero.org/`
- Language: `en`
- Categories: `program-update`
- Maintainers: `jasongzy`
- Source Location: `versions.ts`
- Source Module: `() => import('@/routes/zotero/versions.ts')`

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
  - `zotero.org/`
  - `zotero.org/support/changelog`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "example": "/zotero/versions",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "versions.ts",
  "maintainers": [
    "jasongzy"
  ],
  "module": "() => import('@/routes/zotero/versions.ts')",
  "name": "Version History",
  "parameters": {},
  "path": "/versions",
  "radar": [
    {
      "source": [
        "zotero.org/",
        "zotero.org/support/changelog"
      ]
    }
  ],
  "url": "zotero.org/"
}
```
