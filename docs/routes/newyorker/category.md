# New Yorker - Articles

## Coverage
`index-only`

## Route
- Namespace: `newyorker`
- Namespace Name: `New Yorker`
- Route Path: `/:category`
- Route Name: `Articles`
- Example: `/newyorker/latest`
- URL: `newyorker.com`
- Language: `en`
- Categories: `traditional-media`
- Maintainers: `EthanWng97, pseudoyu`
- Source Location: `news.ts`
- Source Module: `() => import('@/routes/newyorker/news.ts')`

## Description
_None_

## Parameters
- `category`: tab name. can be found at url


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
  - `newyorker.com/:category?`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/newyorker/latest",
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
    "EthanWng97",
    "pseudoyu"
  ],
  "module": "() => import('@/routes/newyorker/news.ts')",
  "name": "Articles",
  "parameters": {
    "category": "tab name. can be found at url"
  },
  "path": "/:category",
  "radar": [
    {
      "source": [
        "newyorker.com/:category?"
      ]
    }
  ],
  "view": 0
}
```
