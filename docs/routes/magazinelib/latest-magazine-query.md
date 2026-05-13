# MagazineLib - Latest Magazine

## Coverage
`index-only`

## Route
- Namespace: `magazinelib`
- Namespace Name: `MagazineLib`
- Route Path: `/latest-magazine/:query?`
- Route Name: `Latest Magazine`
- Example: `/magazinelib/latest-magazine/new+yorker`
- URL: `magazinelib.com`
- Language: `en`
- Categories: `reading`
- Maintainers: `EthanWng97`
- Source Location: `latest-magazine.tsx`
- Source Module: `() => import('@/routes/magazinelib/latest-magazine.tsx')`

## Description
For instance, when doing search at [https://magazinelib.com](https://magazinelib.com) and you get url `https://magazinelib.com/?s=new+yorker`, the query is `new+yorker`

## Parameters
- `query`: query, search page querystring


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
    "reading"
  ],
  "description": "For instance, when doing search at [https://magazinelib.com](https://magazinelib.com) and you get url `https://magazinelib.com/?s=new+yorker`, the query is `new+yorker`",
  "example": "/magazinelib/latest-magazine/new+yorker",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "latest-magazine.tsx",
  "maintainers": [
    "EthanWng97"
  ],
  "module": "() => import('@/routes/magazinelib/latest-magazine.tsx')",
  "name": "Latest Magazine",
  "parameters": {
    "query": "query, search page querystring"
  },
  "path": "/latest-magazine/:query?"
}
```
