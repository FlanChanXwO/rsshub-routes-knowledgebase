# Público - Public

## Coverage
`index-only`

## Route
- Namespace: `publico`
- Namespace Name: `Público`
- Route Path: `/public`
- Route Name: `Public`
- Example: `/publico/public`
- URL: `publico.es`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `adrianrico97`
- Source Location: `public.ts`
- Source Module: `() => import('@/routes/publico/public.ts')`

## Description
_None_

## Parameters
_None_


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
  - `publico.es/public`
- `target`: `/public`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/publico/public",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "public.ts",
  "maintainers": [
    "adrianrico97"
  ],
  "module": "() => import('@/routes/publico/public.ts')",
  "name": "Public",
  "path": "/public",
  "radar": [
    {
      "source": [
        "publico.es/public"
      ],
      "target": "/public"
    }
  ]
}
```
