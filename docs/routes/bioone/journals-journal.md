# BioOne - Journals

## Coverage
`index-only`

## Route
- Namespace: `bioone`
- Namespace Name: `BioOne`
- Route Path: `/journals/:journal?`
- Route Name: `Journals`
- Example: `/bioone/journals/acta-chiropterologica`
- URL: `bioone.org`
- Language: `en`
- Categories: `journal`
- Maintainers: `nczitzk`
- Source Location: `journal.ts`
- Source Module: `() => import('@/routes/bioone/journal.ts')`

## Description
_None_

## Parameters
- `journal`: Journals, can be found in URL


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
  - `bioone.org/journals/:journal`
  - `bioone.org/`
- `target`: `/journals/:journal`

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "example": "/bioone/journals/acta-chiropterologica",
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
  "module": "() => import('@/routes/bioone/journal.ts')",
  "name": "Journals",
  "parameters": {
    "journal": "Journals, can be found in URL"
  },
  "path": "/journals/:journal?",
  "radar": [
    {
      "source": [
        "bioone.org/journals/:journal",
        "bioone.org/"
      ],
      "target": "/journals/:journal"
    }
  ]
}
```
