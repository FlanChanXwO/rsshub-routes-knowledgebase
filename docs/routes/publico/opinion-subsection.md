# Público - Opinión

## Coverage
`index-only`

## Route
- Namespace: `publico`
- Namespace Name: `Público`
- Route Path: `/opinion/:subsection?`
- Route Name: `Opinión`
- Example: `/publico/opinion`
- URL: `publico.es`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `adrianrico97`
- Source Location: `opinion.ts`
- Source Module: `() => import('@/routes/publico/opinion.ts')`

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
  - `publico.es/opinion`
- `target`: `/opinion`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/publico/opinion",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "opinion.ts",
  "maintainers": [
    "adrianrico97"
  ],
  "module": "() => import('@/routes/publico/opinion.ts')",
  "name": "Opinión",
  "parameters": {
    "subsection": {
      "description": "Filter by subsection. Check the subsections available on the newspaper's website."
    }
  },
  "path": "/opinion/:subsection?",
  "radar": [
    {
      "source": [
        "publico.es/opinion"
      ],
      "target": "/opinion"
    }
  ]
}
```
