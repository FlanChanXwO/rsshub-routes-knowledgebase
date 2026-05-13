# 乳首ふぇち - Search

## Coverage
`index-only`

## Route
- Namespace: `chikubi`
- Namespace Name: `乳首ふぇち`
- Route Path: `/search/:keyword`
- Route Name: `Search`
- Example: `/chikubi/search/ギャップ`
- URL: `chikubi.jp`
- Language: `ja`
- Categories: `multimedia`
- Maintainers: `SnowAgar25`
- Source Location: `search.ts`
- Source Module: `() => import('@/routes/chikubi/search.ts')`

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
    "multimedia"
  ],
  "example": "/chikubi/search/ギャップ",
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
  "module": "() => import('@/routes/chikubi/search.ts')",
  "name": "Search",
  "parameters": {
    "keyword": "Keyword"
  },
  "path": "/search/:keyword"
}
```
