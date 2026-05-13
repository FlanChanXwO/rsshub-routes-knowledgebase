# SYCL - Feeds

## Coverage
`index-only`

## Route
- Namespace: `sycl`
- Namespace Name: `SYCL`
- Route Path: `/sycl/:feed?`
- Route Name: `Feeds`
- Example: `/sycl/news`
- URL: `sycl.tech`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `mocusez`
- Source Location: `feeds.ts`
- Source Module: `_None_`

## Description
| Events | News |  Research Paper  | Videos |
| :----: | :--: | :--------------: | :----: |
| events | news | research\_papers | videos |

## Parameters
- `feed`: Feed source, defaults to news, references https://feeds.sycl.tech/


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
    "programming"
  ],
  "description": "| Events | News |  Research Paper  | Videos |\n| :----: | :--: | :--------------: | :----: |\n| events | news | research\\_papers | videos |",
  "example": "/sycl/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 1,
  "location": "feeds.ts",
  "maintainers": [
    "mocusez"
  ],
  "name": "Feeds",
  "parameters": {
    "feed": "Feed source, defaults to news, references https://feeds.sycl.tech/"
  },
  "path": "/:feed?",
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "SYCL.tech news - Powered by RSSHub",
      "errorAt": "2025-11-04T02:43:20.083Z",
      "errorMessage": "Failed to fetch\n",
      "id": "189964261785415680",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://feeds.sycl.tech/news/feed.json",
      "title": "SYCL.tech news",
      "type": "feed",
      "url": "rsshub://sycl"
    }
  ]
}
```
