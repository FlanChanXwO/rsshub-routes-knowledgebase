# Nature Journal - Nature News

## Coverage
`index-only`

## Route
- Namespace: `nature`
- Namespace Name: `Nature Journal`
- Route Path: `/nature/news`
- Route Name: `Nature News`
- Example: `/nature/news`
- URL: `nature.com/latest-news`
- Language: `_None_`
- Categories: `journal`
- Maintainers: `y9c, TonyRL`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: true

## Radar
### Rule 1
- `source`:
  - `nature.com/latest-news`
  - `nature.com/news`
  - `nature.com/`

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "example": "/nature/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": true
  },
  "heat": 311,
  "location": "news.ts",
  "maintainers": [
    "y9c",
    "TonyRL"
  ],
  "name": "Nature News",
  "parameters": {},
  "path": "/news",
  "radar": [
    {
      "source": [
        "nature.com/latest-news",
        "nature.com/news",
        "nature.com/"
      ]
    }
  ],
  "topFeeds": [
    {
      "description": "Browse the latest news from the world's leading research journal. - Powered by RSSHub",
      "errorAt": "2026-06-19T20:42:09.170Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\nthis route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "79390521827702784",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.nature.com/latest-news",
      "title": "Nature | Latest News",
      "type": "feed",
      "url": "rsshub://nature/news"
    }
  ],
  "url": "nature.com/latest-news"
}
```
