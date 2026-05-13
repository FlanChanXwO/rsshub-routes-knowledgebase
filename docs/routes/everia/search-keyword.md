# EVERIA.CLUB - Search

## Coverage
`index-only`

## Route
- Namespace: `everia`
- Namespace Name: `EVERIA.CLUB`
- Route Path: `/search/:keyword`
- Route Name: `Search`
- Example: `/everia/search/日向坂46`
- URL: `everia.club`
- Language: `_None_`
- Categories: `picture`
- Maintainers: `KTachibanaM, AiraNadih`
- Source Location: `search.ts`
- Source Module: `() => import('@/routes/everia/search.ts')`

## Description
_None_

## Parameters
- `keyword`: Keyword


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "example": "/everia/search/日向坂46",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "search.ts",
  "maintainers": [
    "KTachibanaM",
    "AiraNadih"
  ],
  "module": "() => import('@/routes/everia/search.ts')",
  "name": "Search",
  "parameters": {
    "keyword": "Keyword"
  },
  "path": "/search/:keyword"
}
```
