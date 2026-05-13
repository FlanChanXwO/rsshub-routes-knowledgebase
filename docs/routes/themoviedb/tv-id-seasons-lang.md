# The Movie Database - TV Show Seasons

## Coverage
`index-only`

## Route
- Namespace: `themoviedb`
- Namespace Name: `The Movie Database`
- Route Path: `/tv/:id/seasons/:lang?`
- Route Name: `TV Show Seasons`
- Example: `/themoviedb/tv/70593/seasons/en-US`
- URL: `themoviedb.org`
- Language: `en`
- Categories: `multimedia`
- Maintainers: `x2cf`
- Source Location: `seasons.ts`
- Source Module: `() => import('@/routes/themoviedb/seasons.ts')`

## Description
_None_

## Parameters
- `id`: TV show ID
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
  "example": "/themoviedb/tv/70593/seasons/en-US",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "seasons.ts",
  "maintainers": [
    "x2cf"
  ],
  "module": "() => import('@/routes/themoviedb/seasons.ts')",
  "name": "TV Show Seasons",
  "parameters": {
    "id": "TV show ID",
    "lang": "Language"
  },
  "path": "/tv/:id/seasons/:lang?",
  "view": 5
}
```
