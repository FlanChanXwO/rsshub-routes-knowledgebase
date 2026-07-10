# Público - Culturas

## Coverage
`index-only`

## Route
- Namespace: `publico`
- Namespace Name: `Público`
- Route Path: `/publico/culturas/:subsection?`
- Route Name: `Culturas`
- Example: `/publico/culturas`
- URL: `publico.es`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `adrianrico97`
- Source Location: `culturas.ts`
- Source Module: `_None_`

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
  - `publico.es/culturas`
- `target`: `/culturas`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/publico/culturas",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "culturas.ts",
  "maintainers": [
    "adrianrico97"
  ],
  "name": "Culturas",
  "parameters": {
    "subsection": {
      "description": "Filter by subsection. Check the subsections available on the newspaper's website."
    }
  },
  "path": "/culturas/:subsection?",
  "radar": [
    {
      "source": [
        "publico.es/culturas"
      ],
      "target": "/culturas"
    }
  ],
  "topFeeds": []
}
```
