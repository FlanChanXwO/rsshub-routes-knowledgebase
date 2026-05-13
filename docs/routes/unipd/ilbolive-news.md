# Università di Padova - Il Bo Live - News

## Coverage
`index-only`

## Route
- Namespace: `unipd`
- Namespace Name: `Università di Padova`
- Route Path: `/ilbolive/news`
- Route Name: `Il Bo Live - News`
- Example: `/unipd/ilbolive/news`
- URL: `ilbolive.unipd.it/it/news`
- Language: `it`
- Categories: `university`
- Maintainers: `Gexi0619`
- Source Location: `ilbolive/news.ts`
- Source Module: `() => import('@/routes/unipd/ilbolive/news.ts')`

## Description
Il Bo Live - News

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
  - `ilbolive.unipd.it/it/news`
- `target`: `/ilbolive/news`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "Il Bo Live - News",
  "example": "/unipd/ilbolive/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "ilbolive/news.ts",
  "maintainers": [
    "Gexi0619"
  ],
  "module": "() => import('@/routes/unipd/ilbolive/news.ts')",
  "name": "Il Bo Live - News",
  "parameters": {},
  "path": "/ilbolive/news",
  "radar": [
    {
      "source": [
        "ilbolive.unipd.it/it/news"
      ],
      "target": "/ilbolive/news"
    }
  ],
  "url": "ilbolive.unipd.it/it/news"
}
```
