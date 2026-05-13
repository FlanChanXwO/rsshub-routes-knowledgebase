# The University of Chicago Press: Journals - Current Issue

## Coverage
`index-only`

## Route
- Namespace: `uchicago`
- Namespace Name: `The University of Chicago Press: Journals`
- Route Path: `/journals/current/:journal`
- Route Name: `Current Issue`
- Example: `/uchicago/journals/current/jpe`
- URL: `journals.uchicago.edu`
- Language: `en`
- Categories: `journal`
- Maintainers: `TonyRL`
- Source Location: `current.ts`
- Source Module: `() => import('@/routes/uchicago/current.ts')`

## Description
_None_

## Parameters
- `journal`: Journal id, can be found in URL. [Browse journals by title](https://www.journals.uchicago.edu/action/showPublications)


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `journals.uchicago.edu/toc/:journal/current`
  - `journals.uchicago.edu/journal/:journal`

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "example": "/uchicago/journals/current/jpe",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "current.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/uchicago/current.ts')",
  "name": "Current Issue",
  "parameters": {
    "journal": "Journal id, can be found in URL. [Browse journals by title](https://www.journals.uchicago.edu/action/showPublications)"
  },
  "path": "/journals/current/:journal",
  "radar": [
    {
      "source": [
        "journals.uchicago.edu/toc/:journal/current",
        "journals.uchicago.edu/journal/:journal"
      ]
    }
  ]
}
```
