# Público - Ciencias

## Coverage
`index-only`

## Route
- Namespace: `publico`
- Namespace Name: `Público`
- Route Path: `/ciencias/:subsection?`
- Route Name: `Ciencias`
- Example: `/publico/ciencias`
- URL: `publico.es`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `adrianrico97`
- Source Location: `ciencias.ts`
- Source Module: `() => import('@/routes/publico/ciencias.ts')`

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
  - `publico.es/ciencias`
- `target`: `/ciencias`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/publico/ciencias",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "ciencias.ts",
  "maintainers": [
    "adrianrico97"
  ],
  "module": "() => import('@/routes/publico/ciencias.ts')",
  "name": "Ciencias",
  "parameters": {
    "subsection": {
      "description": "Filter by subsection. Check the subsections available on the newspaper's website."
    }
  },
  "path": "/ciencias/:subsection?",
  "radar": [
    {
      "source": [
        "publico.es/ciencias"
      ],
      "target": "/ciencias"
    }
  ]
}
```
