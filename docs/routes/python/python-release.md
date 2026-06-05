# Python - Active Python Releases

## Coverage
`index-only`

## Route
- Namespace: `python`
- Namespace Name: `Python`
- Route Path: `/python/release`
- Route Name: `Active Python Releases`
- Example: `/python/release`
- URL: `www.python.org`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `nczitzk`
- Source Location: `release.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.python.org`
  - `www.python.org/downloads`
- `target`: `/release`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/python/release",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 79,
  "location": "release.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Active Python Releases",
  "path": "/release",
  "radar": [
    {
      "source": [
        "www.python.org",
        "www.python.org/downloads"
      ],
      "target": "/release"
    }
  ],
  "topFeeds": [
    {
      "description": "The official home of the Python Programming Language - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "160122574224355328",
      "image": "https://www.python.org/static/opengraph-icon-200x200.png",
      "ownerUserId": null,
      "siteUrl": "https://www.python.org/downloads",
      "title": "Active Python releases",
      "type": "feed",
      "url": "rsshub://python/release"
    }
  ],
  "url": "www.python.org",
  "view": 0
}
```
