# Sky Sports - News

## Coverage
`index-only`

## Route
- Namespace: `skysports`
- Namespace Name: `Sky Sports`
- Route Path: `/news/:team`
- Route Name: `News`
- Example: `/skysports/news/ac-milan`
- URL: `skysports.com`
- Language: `en`
- Categories: `sport`
- Maintainers: `nczitzk`
- Source Location: `news.ts`
- Source Module: `() => import('@/routes/skysports/news.ts')`

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
  "location": "news.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/skysports/news.ts')",
  "name": "News",
  "parameters": {
    "team": "Team id, can be found in URL to the team page"
  },
  "path": "/news/:team"
}
```
