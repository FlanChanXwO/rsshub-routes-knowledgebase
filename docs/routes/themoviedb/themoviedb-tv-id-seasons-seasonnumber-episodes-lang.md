# The Movie Database - TV Show Episodes

## Coverage
`index-only`

## Route
- Namespace: `themoviedb`
- Namespace Name: `The Movie Database`
- Route Path: `/themoviedb/tv/:id/seasons/:seasonNumber/episodes/:lang?`
- Route Name: `TV Show Episodes`
- Example: `/themoviedb/tv/70593/seasons/1/episodes/en-US`
- URL: `themoviedb.org`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `x2cf`
- Source Location: `episodes.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: TV show ID
- `seasonNumber`: Season number
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
  "example": "/themoviedb/tv/70593/seasons/1/episodes/en-US",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "episodes.ts",
  "maintainers": [
    "x2cf"
  ],
  "name": "TV Show Episodes",
  "parameters": {
    "id": "TV show ID",
    "lang": "Language",
    "seasonNumber": "Season number"
  },
  "path": "/tv/:id/seasons/:seasonNumber/episodes/:lang?",
  "topFeeds": []
}
```
