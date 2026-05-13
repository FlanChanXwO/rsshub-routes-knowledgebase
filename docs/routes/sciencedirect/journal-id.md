# ScienceDirect - Journal

## Coverage
`index-only`

## Route
- Namespace: `sciencedirect`
- Namespace Name: `ScienceDirect`
- Route Path: `/journal/:id`
- Route Name: `Journal`
- Example: `/sciencedirect/journal/research-policy`
- URL: `sciencedirect.com`
- Language: `en`
- Categories: `journal`
- Maintainers: `nczitzk`
- Source Location: `journal.ts`
- Source Module: `() => import('@/routes/sciencedirect/journal.ts')`

## Description
_None_

## Parameters
- `id`: Journal id, can be found in URL


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
  - `sciencedirect.com/journal/:id`
  - `sciencedirect.com/`

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "example": "/sciencedirect/journal/research-policy",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "journal.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/sciencedirect/journal.ts')",
  "name": "Journal",
  "parameters": {
    "id": "Journal id, can be found in URL"
  },
  "path": "/journal/:id",
  "radar": [
    {
      "source": [
        "sciencedirect.com/journal/:id",
        "sciencedirect.com/"
      ]
    }
  ]
}
```
