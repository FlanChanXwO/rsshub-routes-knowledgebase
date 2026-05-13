# Annual Reviews - Journal

## Coverage
`index-only`

## Route
- Namespace: `annualreviews`
- Namespace Name: `Annual Reviews`
- Route Path: `/:id`
- Route Name: `Journal`
- Example: `/annualreviews/anchem`
- URL: `annualreviews.org`
- Language: `en`
- Categories: `journal`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/annualreviews/index.ts')`

## Description
The URL of the journal [Annual Review of Analytical Chemistry](https://www.annualreviews.org/journal/anchem) is `https://www.annualreviews.org/journal/anchem`, where `anchem` is the id of the journal, so the route for this journal is `/annualreviews/anchem`.

::: tip
  More jounals can be found in [Browse Journals](https://www.annualreviews.org/action/showPublications).
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
  - `annualreviews.org/journal/:id`
  - `annualreviews.org/`

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "description": "The URL of the journal [Annual Review of Analytical Chemistry](https://www.annualreviews.org/journal/anchem) is `https://www.annualreviews.org/journal/anchem`, where `anchem` is the id of the journal, so the route for this journal is `/annualreviews/anchem`.\n\n::: tip\n  More jounals can be found in [Browse Journals](https://www.annualreviews.org/action/showPublications).\n:::",
  "example": "/annualreviews/anchem",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": true
  },
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/annualreviews/index.ts')",
  "name": "Journal",
  "parameters": {
    "id": "Journal id, can be found in URL"
  },
  "path": "/:id",
  "radar": [
    {
      "source": [
        "annualreviews.org/journal/:id",
        "annualreviews.org/"
      ]
    }
  ]
}
```
