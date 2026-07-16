# TechCrunch - News

## Coverage
`index-only`

## Route
- Namespace: `techcrunch`
- Namespace Name: `TechCrunch`
- Route Path: `/techcrunch/news`
- Route Name: `News`
- Example: `/techcrunch/news`
- URL: `techcrunch.com/`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `EthanWng97`
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
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `techcrunch.com/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/techcrunch/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 625,
  "location": "news.ts",
  "maintainers": [
    "EthanWng97"
  ],
  "name": "News",
  "parameters": {},
  "path": "/news",
  "radar": [
    {
      "source": [
        "techcrunch.com/"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Reporting on the business of technology, startups, venture capital funding, and Silicon Valley. - Powered by RSSHub",
      "errorAt": "2026-07-15T05:32:08.597Z",
      "errorMessage": "Failed query: select \"id\", \"guid\", \"media\" from \"entries\" \"entries\" where \"entries\".\"feed_id\" = $1\nparams: 41572238273905682",
      "id": "41572238273905682",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://techcrunch.com/",
      "title": "TechCrunch",
      "type": "feed",
      "url": "rsshub://techcrunch/news"
    }
  ],
  "url": "techcrunch.com/"
}
```
