# Público - Internacional

## Coverage
`index-only`

## Route
- Namespace: `publico`
- Namespace Name: `Público`
- Route Path: `/internacional/:subsection?`
- Route Name: `Internacional`
- Example: `/publico/internacional`
- URL: `publico.es`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `adrianrico97`
- Source Location: `internacional.ts`
- Source Module: `() => import('@/routes/publico/internacional.ts')`

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
  - `publico.es/internacional`
- `target`: `/internacional`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/publico/internacional",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "internacional.ts",
  "maintainers": [
    "adrianrico97"
  ],
  "module": "() => import('@/routes/publico/internacional.ts')",
  "name": "Internacional",
  "parameters": {
    "subsection": {
      "description": "Filter by subsection. Check the subsections available on the newspaper's website."
    }
  },
  "path": "/internacional/:subsection?",
  "radar": [
    {
      "source": [
        "publico.es/internacional"
      ],
      "target": "/internacional"
    }
  ]
}
```
