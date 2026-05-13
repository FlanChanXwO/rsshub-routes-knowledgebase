# Público - Economia

## Coverage
`index-only`

## Route
- Namespace: `publico`
- Namespace Name: `Público`
- Route Path: `/economia/:subsection?`
- Route Name: `Economia`
- Example: `/publico/economia`
- URL: `publico.es`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `adrianrico97`
- Source Location: `economia.ts`
- Source Module: `() => import('@/routes/publico/economia.ts')`

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
  - `publico.es/economia`
- `target`: `/economia`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/publico/economia",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "economia.ts",
  "maintainers": [
    "adrianrico97"
  ],
  "module": "() => import('@/routes/publico/economia.ts')",
  "name": "Economia",
  "parameters": {
    "subsection": {
      "description": "Filter by subsection. Check the subsections available on the newspaper's website."
    }
  },
  "path": "/economia/:subsection?",
  "radar": [
    {
      "source": [
        "publico.es/economia"
      ],
      "target": "/economia"
    }
  ]
}
```
