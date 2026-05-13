# DBLP - Keyword Search

## Coverage
`index-only`

## Route
- Namespace: `dblp`
- Namespace Name: `DBLP`
- Route Path: `/:field`
- Route Name: `Keyword Search`
- Example: `/dblp/knowledge%20tracing`
- URL: `dblp.org`
- Language: `en`
- Categories: `study`
- Maintainers: `ytno1`
- Source Location: `publication.ts`
- Source Module: `() => import('@/routes/dblp/publication.ts')`

## Description
_None_

## Parameters
- `field`: Research field


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `dblp.org/:field`

## Raw JSON
```json
{
  "categories": [
    "study"
  ],
  "example": "/dblp/knowledge%20tracing",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "publication.ts",
  "maintainers": [
    "ytno1"
  ],
  "module": "() => import('@/routes/dblp/publication.ts')",
  "name": "Keyword Search",
  "parameters": {
    "field": "Research field"
  },
  "path": "/:field",
  "radar": [
    {
      "source": [
        "dblp.org/:field"
      ]
    }
  ]
}
```
