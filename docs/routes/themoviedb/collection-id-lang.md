# The Movie Database - Collection

## Coverage
`index-only`

## Route
- Namespace: `themoviedb`
- Namespace Name: `The Movie Database`
- Route Path: `/collection/:id/:lang?`
- Route Name: `Collection`
- Example: `/themoviedb/collection/131292/en-US`
- URL: `themoviedb.org`
- Language: `en`
- Categories: `multimedia`
- Maintainers: `x2cf`
- Source Location: `collection.ts`
- Source Module: `() => import('@/routes/themoviedb/collection.ts')`

## Description
_None_

## Parameters
- `id`: Collection ID
- `lang`: Language


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/themoviedb/collection/131292/en-US",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "collection.ts",
  "maintainers": [
    "x2cf"
  ],
  "module": "() => import('@/routes/themoviedb/collection.ts')",
  "name": "Collection",
  "parameters": {
    "id": "Collection ID",
    "lang": "Language"
  },
  "path": "/collection/:id/:lang?"
}
```
