# Sky Sports - News

## Coverage
`index-only`

## Route
- Namespace: `skysports`
- Namespace Name: `Sky Sports`
- Route Path: `/skysports/news/:team`
- Route Name: `News`
- Example: `/skysports/news/ac-milan`
- URL: `skysports.com`
- Language: `_None_`
- Categories: `sport`
- Maintainers: `nczitzk`
- Source Location: `news.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `team`: Team id, can be found in URL to the team page


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
    "sport"
  ],
  "example": "/skysports/news/ac-milan",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "news.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "News",
  "parameters": {
    "team": "Team id, can be found in URL to the team page"
  },
  "path": "/news/:team",
  "topFeeds": []
}
```
