# Plurk - Plurk News

## Coverage
`index-only`

## Route
- Namespace: `plurk`
- Namespace Name: `Plurk`
- Route Path: `/plurk/news/:lang?`
- Route Name: `Plurk News`
- Example: `/plurk/news/:lang?`
- URL: `plurk.com/news`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `TonyRL`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `lang`: Language, see the table above, `en` by default


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
  - `plurk.com/news`
- `target`: `/news`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/plurk/news/:lang?",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 8,
  "location": "news.ts",
  "maintainers": [
    "TonyRL"
  ],
  "name": "Plurk News",
  "parameters": {
    "lang": "Language, see the table above, `en` by default"
  },
  "path": "/news/:lang?",
  "radar": [
    {
      "source": [
        "plurk.com/news"
      ],
      "target": "/news"
    }
  ],
  "topFeeds": [
    {
      "description": "Plurk News - Plurk - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "85124888669554688",
      "image": "https://s.plurk.com/2c1574c02566f3b06e91.png",
      "ownerUserId": null,
      "siteUrl": "https://www.plurk.com/news",
      "title": "Plurk News - Plurk",
      "type": "feed",
      "url": "rsshub://plurk/news"
    }
  ],
  "url": "plurk.com/news"
}
```
