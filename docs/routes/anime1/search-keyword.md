# Anime1 - Search

## Coverage
`index-only`

## Route
- Namespace: `anime1`
- Namespace Name: `Anime1`
- Route Path: `search/:keyword`
- Route Name: `Search`
- Example: `/anime1/search/神之塔`
- URL: `anime1.me`
- Language: `zh-TW`
- Categories: `anime`
- Maintainers: `cxheng315`
- Source Location: `search.ts`
- Source Module: `() => import('@/routes/anime1/search.ts')`

## Description
_None_

## Parameters
- `keyword`: Anime1 Search Keyword


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
    "anime"
  ],
  "example": "/anime1/search/神之塔",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "search.ts",
  "maintainers": [
    "cxheng315"
  ],
  "module": "() => import('@/routes/anime1/search.ts')",
  "name": "Search",
  "parameters": {
    "keyword": "Anime1 Search Keyword"
  },
  "path": "search/:keyword",
  "url": "anime1.me"
}
```
