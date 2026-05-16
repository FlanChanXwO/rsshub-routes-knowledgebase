# Público - Ciencias

## Coverage
`index-only`

## Route
- Namespace: `publico`
- Namespace Name: `Público`
- Route Path: `/publico/ciencias/:subsection?`
- Route Name: `Ciencias`
- Example: `/publico/ciencias`
- URL: `publico.es`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `adrianrico97`
- Source Location: `ciencias.ts`
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
  "heat": 3,
  "location": "ciencias.ts",
  "maintainers": [
    "adrianrico97"
  ],
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
  ],
  "topFeeds": [
    {
      "description": "Ciencias | Público - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "111690051929742336",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.publico.es/ciencias",
      "title": "Ciencias | Público",
      "type": "feed",
      "url": "rsshub://publico/ciencias"
    }
  ]
}
```
