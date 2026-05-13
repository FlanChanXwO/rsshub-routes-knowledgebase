# American Economic Association - Journal

## Coverage
`index-only`

## Route
- Namespace: `aeaweb`
- Namespace Name: `American Economic Association`
- Route Path: `/:id`
- Route Name: `Journal`
- Example: `/aeaweb/aer`
- URL: `aeaweb.org`
- Language: `en`
- Categories: `journal`
- Maintainers: `nczitzk`
- Source Location: `index.tsx`
- Source Module: `() => import('@/routes/aeaweb/index.tsx')`

## Description
The URL of the journal [American Economic Review](https://www.aeaweb.org/journals/aer) is `https://www.aeaweb.org/journals/aer`, where `aer` is the id of the journal, so the route for this journal is `/aeaweb/aer`.

::: tip
  More jounals can be found in [AEA Journals](https://www.aeaweb.org/journals).
:::

## Parameters
- `id`: Journal id, can be found in URL


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: true

## Radar
### Rule 1
- `source`:
  - `aeaweb.org/journals/:id`
  - `aeaweb.org/`

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "description": "The URL of the journal [American Economic Review](https://www.aeaweb.org/journals/aer) is `https://www.aeaweb.org/journals/aer`, where `aer` is the id of the journal, so the route for this journal is `/aeaweb/aer`.\n\n::: tip\n  More jounals can be found in [AEA Journals](https://www.aeaweb.org/journals).\n:::",
  "example": "/aeaweb/aer",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": true
  },
  "location": "index.tsx",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/aeaweb/index.tsx')",
  "name": "Journal",
  "parameters": {
    "id": "Journal id, can be found in URL"
  },
  "path": "/:id",
  "radar": [
    {
      "source": [
        "aeaweb.org/journals/:id",
        "aeaweb.org/"
      ]
    }
  ]
}
```
