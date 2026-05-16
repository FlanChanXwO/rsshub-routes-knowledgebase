# BaoBua - Search

## Coverage
`index-only`

## Route
- Namespace: `baobua`
- Namespace Name: `BaoBua`
- Route Path: `/baobua/search/:keyword`
- Route Name: `Search`
- Example: `/baobua/search/cos`
- URL: `baobua.com/`
- Language: `_None_`
- Categories: `picture`
- Maintainers: `AiraNadih`
- Source Location: `search.ts`
- Source Module: `_None_`

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

## Radar
### Rule 1
- `source`:
  - `baobua.com/search`
- `target`: `/search/:keyword`

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "example": "/baobua/search/cos",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 14,
  "location": "search.ts",
  "maintainers": [
    "AiraNadih"
  ],
  "name": "Search",
  "parameters": {
    "keyword": "Keyword"
  },
  "path": "/search/:keyword",
  "radar": [
    {
      "source": [
        "baobua.com/search"
      ],
      "target": "/search/:keyword"
    }
  ],
  "topFeeds": [
    {
      "description": "BaoBua - Search: cos - Powered by RSSHub",
      "errorAt": "2025-09-16T08:49:09.640Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "131498387978345472",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://baobua.com/search?q=cos",
      "title": "BaoBua - Search: cos",
      "type": "feed",
      "url": "rsshub://baobua/search/cos"
    }
  ],
  "url": "baobua.com/"
}
```
