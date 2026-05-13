# MDPI - Journal

## Coverage
`index-only`

## Route
- Namespace: `mdpi`
- Namespace Name: `MDPI`
- Route Path: `/:journal`
- Route Name: `Journal`
- Example: `/mdpi/analytica`
- URL: `www.mdpi.com`
- Language: `en`
- Categories: `journal`
- Maintainers: `Derekmini`
- Source Location: `journal.tsx`
- Source Module: `() => import('@/routes/mdpi/journal.tsx')`

## Description
_None_

## Parameters
- `journal`: Journal Name, get it from the journal homepage


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
  - `www.mdpi.com/journal/:journal`

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "example": "/mdpi/analytica",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "journal.tsx",
  "maintainers": [
    "Derekmini"
  ],
  "module": "() => import('@/routes/mdpi/journal.tsx')",
  "name": "Journal",
  "parameters": {
    "journal": "Journal Name, get it from the journal homepage"
  },
  "path": "/:journal",
  "radar": [
    {
      "source": [
        "www.mdpi.com/journal/:journal"
      ]
    }
  ]
}
```
