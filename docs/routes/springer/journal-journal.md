# Springer - Journal

## Coverage
`index-only`

## Route
- Namespace: `springer`
- Namespace Name: `Springer`
- Route Path: `/journal/:journal`
- Route Name: `Journal`
- Example: `/springer/journal/10450`
- URL: `www.springer.com`
- Language: `en`
- Categories: `journal`
- Maintainers: `Derekmini, TonyRL, xiahaoyun`
- Source Location: `journal.tsx`
- Source Module: `() => import('@/routes/springer/journal.tsx')`

## Description
_None_

## Parameters
- `journal`: Journal Code, the number in the URL from the journal homepage


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
  - `www.springer.com/journal/:journal/*`

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "example": "/springer/journal/10450",
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
    "Derekmini",
    "TonyRL",
    "xiahaoyun"
  ],
  "module": "() => import('@/routes/springer/journal.tsx')",
  "name": "Journal",
  "parameters": {
    "journal": "Journal Code, the number in the URL from the journal homepage"
  },
  "path": "/journal/:journal",
  "radar": [
    {
      "source": [
        "www.springer.com/journal/:journal/*"
      ]
    }
  ]
}
```
