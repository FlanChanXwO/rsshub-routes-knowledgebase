# Science Magazine - First Release

## Coverage
`index-only`

## Route
- Namespace: `science`
- Namespace Name: `Science Magazine`
- Route Path: `/early/:journal?`
- Route Name: `First Release`
- Example: `/science/early`
- URL: `science.org`
- Language: `en`
- Categories: `journal`
- Maintainers: `y9c, TonyRL`
- Source Location: `early.ts`
- Source Module: `() => import('@/routes/science/early.ts')`

## Description
*only Science, Science Immunology and Science Translational Medicine have first release*

## Parameters
- `journal`: Short name for a journal


## Features
- `requireConfig`: false
- `requirePuppeteer`: true
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: true

## Radar
### Rule 1
- `source`:
  - `science.org/journal/:journal`
  - `science.org/toc/:journal/0/0`
- `target`: `/early/:journal`

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "description": "*only Science, Science Immunology and Science Translational Medicine have first release*",
  "example": "/science/early",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": true
  },
  "location": "early.ts",
  "maintainers": [
    "y9c",
    "TonyRL"
  ],
  "module": "() => import('@/routes/science/early.ts')",
  "name": "First Release",
  "parameters": {
    "journal": "Short name for a journal"
  },
  "path": "/early/:journal?",
  "radar": [
    {
      "source": [
        "science.org/journal/:journal",
        "science.org/toc/:journal/0/0"
      ],
      "target": "/early/:journal"
    }
  ]
}
```
