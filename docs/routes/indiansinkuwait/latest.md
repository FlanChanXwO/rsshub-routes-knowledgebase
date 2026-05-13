# Indians in Kuwait - News

## Coverage
`index-only`

## Route
- Namespace: `indiansinkuwait`
- Namespace Name: `Indians in Kuwait`
- Route Path: `/latest`
- Route Name: `News`
- Example: `/indiansinkuwait/latest`
- URL: `indiansinkuwait.com/latest-news`
- Language: `en`
- Categories: `new-media`
- Maintainers: `TonyRL`
- Source Location: `latest.ts`
- Source Module: `() => import('@/routes/indiansinkuwait/latest.ts')`

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
  - `indiansinkuwait.com/latest-news`
  - `indiansinkuwait.com/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/indiansinkuwait/latest",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "latest.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/indiansinkuwait/latest.ts')",
  "name": "News",
  "parameters": {},
  "path": "/latest",
  "radar": [
    {
      "source": [
        "indiansinkuwait.com/latest-news",
        "indiansinkuwait.com/"
      ]
    }
  ],
  "url": "indiansinkuwait.com/latest-news"
}
```
