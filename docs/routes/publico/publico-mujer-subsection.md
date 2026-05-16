# Público - Mujer

## Coverage
`index-only`

## Route
- Namespace: `publico`
- Namespace Name: `Público`
- Route Path: `/publico/mujer/:subsection?`
- Route Name: `Mujer`
- Example: `/publico/mujer`
- URL: `publico.es`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `adrianrico97`
- Source Location: `mujer.ts`
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
  - `publico.es/mujer`
- `target`: `/mujer`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/publico/mujer",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "mujer.ts",
  "maintainers": [
    "adrianrico97"
  ],
  "name": "Mujer",
  "parameters": {
    "subsection": {
      "description": "Filter by subsection. Check the subsections available on the newspaper's website."
    }
  },
  "path": "/mujer/:subsection?",
  "radar": [
    {
      "source": [
        "publico.es/mujer"
      ],
      "target": "/mujer"
    }
  ],
  "topFeeds": []
}
```
