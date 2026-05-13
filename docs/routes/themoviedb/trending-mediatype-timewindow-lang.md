# The Movie Database - Trending

## Coverage
`index-only`

## Route
- Namespace: `themoviedb`
- Namespace Name: `The Movie Database`
- Route Path: `/trending/:mediaType/:timeWindow/:lang?`
- Route Name: `Trending`
- Example: `/themoviedb/trending/tv/day/en-US`
- URL: `themoviedb.org`
- Language: `en`
- Categories: `multimedia`
- Maintainers: `x2cf`
- Source Location: `trending.ts`
- Source Module: `() => import('@/routes/themoviedb/trending.ts')`

## Description
_None_

## Parameters
- `mediaType`: `movie` or `tv`
- `timeWindow`: `day` or `week`
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
  "example": "/themoviedb/trending/tv/day/en-US",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "trending.ts",
  "maintainers": [
    "x2cf"
  ],
  "module": "() => import('@/routes/themoviedb/trending.ts')",
  "name": "Trending",
  "parameters": {
    "lang": "Language",
    "mediaType": "`movie` or `tv`",
    "timeWindow": "`day` or `week`"
  },
  "path": "/trending/:mediaType/:timeWindow/:lang?"
}
```
