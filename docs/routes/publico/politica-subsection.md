# Público - Política

## Coverage
`index-only`

## Route
- Namespace: `publico`
- Namespace Name: `Público`
- Route Path: `/politica/:subsection?`
- Route Name: `Política`
- Example: `/publico/politica`
- URL: `publico.es`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `adrianrico97`
- Source Location: `politica.ts`
- Source Module: `() => import('@/routes/publico/politica.ts')`

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
  - `publico.es/politica`
- `target`: `/politica`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/publico/politica",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "politica.ts",
  "maintainers": [
    "adrianrico97"
  ],
  "module": "() => import('@/routes/publico/politica.ts')",
  "name": "Política",
  "parameters": {
    "subsection": {
      "description": "Filter by subsection. Check the subsections available on the newspaper's website."
    }
  },
  "path": "/politica/:subsection?",
  "radar": [
    {
      "source": [
        "publico.es/politica"
      ],
      "target": "/politica"
    }
  ]
}
```
