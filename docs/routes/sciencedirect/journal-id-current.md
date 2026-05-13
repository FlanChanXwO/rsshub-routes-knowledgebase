# ScienceDirect - Current Issue

## Coverage
`index-only`

## Route
- Namespace: `sciencedirect`
- Namespace Name: `ScienceDirect`
- Route Path: `/journal/:id/current`
- Route Name: `Current Issue`
- Example: `/sciencedirect/journal/journal-of-financial-economics/current`
- URL: `sciencedirect.com`
- Language: `en`
- Categories: `journal`
- Maintainers: `TonyRL`
- Source Location: `current-issue.ts`
- Source Module: `() => import('@/routes/sciencedirect/current-issue.ts')`

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
  "example": "/sciencedirect/journal/journal-of-financial-economics/current",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "current-issue.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/sciencedirect/current-issue.ts')",
  "name": "Current Issue",
  "parameters": {
    "id": "Journal id, can be found in URL"
  },
  "path": "/journal/:id/current",
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
