# The Movie Database - Sheet

## Coverage
`index-only`

## Route
- Namespace: `themoviedb`
- Namespace Name: `The Movie Database`
- Route Path: `/:mediaType/:sheet/:lang?`
- Route Name: `Sheet`
- Example: `/themoviedb/tv/top-rated/en-US`
- URL: `themoviedb.org`
- Language: `en`
- Categories: `multimedia`
- Maintainers: `x2cf`
- Source Location: `sheet.ts`
- Source Module: `() => import('@/routes/themoviedb/sheet.ts')`

## Description
When `mediaType` is `tv`, `sheet` should be:

| Airing Today | On TV      | Top Rated |
| ------------ | ---------- | --------- |
| airing-today | on-the-air | top-rated |

  When `mediaType` is `movie`, `sheet` should be:

| Now Playing | Upcoming | Top Rated |
| ----------- | -------- | --------- |
| now-playing | upcoming | top-rated |

## Parameters
- `mediaType`: `movie` or `tv`
- `sheet`: Sheet, see below
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
  "description": "When `mediaType` is `tv`, `sheet` should be:\n\n| Airing Today | On TV      | Top Rated |\n| ------------ | ---------- | --------- |\n| airing-today | on-the-air | top-rated |\n\n  When `mediaType` is `movie`, `sheet` should be:\n\n| Now Playing | Upcoming | Top Rated |\n| ----------- | -------- | --------- |\n| now-playing | upcoming | top-rated |",
  "example": "/themoviedb/tv/top-rated/en-US",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "sheet.ts",
  "maintainers": [
    "x2cf"
  ],
  "module": "() => import('@/routes/themoviedb/sheet.ts')",
  "name": "Sheet",
  "parameters": {
    "lang": "Language",
    "mediaType": "`movie` or `tv`",
    "sheet": "Sheet, see below"
  },
  "path": "/:mediaType/:sheet/:lang?"
}
```
