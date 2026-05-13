# Skeb - Search Results

## Coverage
`index-only`

## Route
- Namespace: `skeb`
- Namespace Name: `Skeb`
- Route Path: `/search/:keyword`
- Route Name: `Search Results`
- Example: `/skeb/search/初音ミク`
- URL: `skeb.jp`
- Language: `ja`
- Categories: `picture`
- Maintainers: `SnowAgar25`
- Source Location: `search.ts`
- Source Module: `() => import('@/routes/skeb/search.ts')`

## Description
Get the search results for works on Skeb

## Parameters
- `keyword`: Search keyword


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
  "description": "Get the search results for works on Skeb",
  "example": "/skeb/search/初音ミク",
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
    "SnowAgar25"
  ],
  "module": "() => import('@/routes/skeb/search.ts')",
  "name": "Search Results",
  "parameters": {
    "keyword": "Search keyword"
  },
  "path": "/search/:keyword"
}
```
