# Skeb - Search Results

## Coverage
`index-only`

## Route
- Namespace: `skeb`
- Namespace Name: `Skeb`
- Route Path: `/skeb/search/:keyword`
- Route Name: `Search Results`
- Example: `/skeb/search/初音ミク`
- URL: `skeb.jp`
- Language: `_None_`
- Categories: `picture`
- Maintainers: `SnowAgar25`
- Source Location: `search.ts`
- Source Module: `_None_`

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
  "heat": 0,
  "location": "search.ts",
  "maintainers": [
    "SnowAgar25"
  ],
  "name": "Search Results",
  "parameters": {
    "keyword": "Search keyword"
  },
  "path": "/search/:keyword",
  "test": {
    "code": 0
  },
  "topFeeds": []
}
```
