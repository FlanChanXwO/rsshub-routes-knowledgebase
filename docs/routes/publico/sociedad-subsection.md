# Público - Sociedad

## Coverage
`index-only`

## Route
- Namespace: `publico`
- Namespace Name: `Público`
- Route Path: `/sociedad/:subsection?`
- Route Name: `Sociedad`
- Example: `/publico/sociedad`
- URL: `publico.es`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `adrianrico97`
- Source Location: `sociedad.ts`
- Source Module: `() => import('@/routes/publico/sociedad.ts')`

## Description
_None_

## Parameters
- `subsection`: {"description": "Filter by subsection. Check the subsections available on the newspaper's website."}


## Features
- `requireConfig`: false
- `requirePuppeteer`: true
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `publico.es/sociedad`
- `target`: `/sociedad`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/publico/sociedad",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "sociedad.ts",
  "maintainers": [
    "adrianrico97"
  ],
  "module": "() => import('@/routes/publico/sociedad.ts')",
  "name": "Sociedad",
  "parameters": {
    "subsection": {
      "description": "Filter by subsection. Check the subsections available on the newspaper's website."
    }
  },
  "path": "/sociedad/:subsection?",
  "radar": [
    {
      "source": [
        "publico.es/sociedad"
      ],
      "target": "/sociedad"
    }
  ]
}
```
