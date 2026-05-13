# Greasy Fork - Script Version History

## Coverage
`index-only`

## Route
- Namespace: `greasyfork`
- Namespace Name: `Greasy Fork`
- Route Path: `/scripts/:script/versions`
- Route Name: `Script Version History`
- Example: `/greasyfork/scripts/431691-bypass-all-shortlinks/versions`
- URL: `greasyfork.org`
- Language: `en`
- Categories: `program-update`
- Maintainers: `miles170`
- Source Location: `versions.ts`
- Source Module: `() => import('@/routes/greasyfork/versions.ts')`

## Description
_None_

## Parameters
- `script`: Script id, can be found in URL


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
  - `greasyfork.org/:language/scripts/:script/versions`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "example": "/greasyfork/scripts/431691-bypass-all-shortlinks/versions",
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
    "miles170"
  ],
  "module": "() => import('@/routes/greasyfork/versions.ts')",
  "name": "Script Version History",
  "parameters": {
    "script": "Script id, can be found in URL"
  },
  "path": "/scripts/:script/versions",
  "radar": [
    {
      "source": [
        "greasyfork.org/:language/scripts/:script/versions"
      ]
    }
  ]
}
```
