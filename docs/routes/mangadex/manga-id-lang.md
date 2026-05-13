# MangaDex - Single Manga Feed

## Coverage
`index-only`

## Route
- Namespace: `mangadex`
- Namespace Name: `MangaDex`
- Route Path: `/manga/:id/:lang?`
- Route Name: `Single Manga Feed`
- Example: `/mangadex/manga/f98660a1-d2e2-461c-960d-7bd13df8b76d/en`
- URL: `mangadex.org`
- Language: `en`
- Categories: `anime`
- Maintainers: `vzz64, chrisis58`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/mangadex/index.ts')`

## Description
_None_

## Parameters
_None_


## Features
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `mangadex.org/title/:id/:suffix`
  - `mangadex.org/title/:id`
- `target`: `/manga/:id`

## Raw JSON
```json
{
  "example": "/mangadex/manga/f98660a1-d2e2-461c-960d-7bd13df8b76d/en",
  "features": {
    "nsfw": true
  },
  "location": "index.ts",
  "maintainers": [
    "vzz64",
    "chrisis58"
  ],
  "module": "() => import('@/routes/mangadex/index.ts')",
  "name": "Single Manga Feed",
  "path": "/manga/:id/:lang?",
  "radar": [
    {
      "source": [
        "mangadex.org/title/:id/:suffix",
        "mangadex.org/title/:id"
      ],
      "target": "/manga/:id"
    }
  ]
}
```
