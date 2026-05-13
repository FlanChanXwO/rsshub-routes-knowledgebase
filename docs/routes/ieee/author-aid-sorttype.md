# IEEE Xplore - IEEE Author Articles

## Coverage
`index-only`

## Route
- Namespace: `ieee`
- Namespace Name: `IEEE Xplore`
- Route Path: `/author/:aid/:sortType`
- Route Name: `IEEE Author Articles`
- Example: `/ieee/author/37264968900/newest`
- URL: `www.ieee.org`
- Language: `en`
- Categories: `journal`
- Maintainers: `Derekmini`
- Source Location: `author.ts`
- Source Module: `() => import('@/routes/ieee/author.ts')`

## Description
_None_

## Parameters
- `aid`: Author ID
- `sortType`: Sort Type of papers


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: true

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "example": "/ieee/author/37264968900/newest",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": true
  },
  "location": "author.ts",
  "maintainers": [
    "Derekmini"
  ],
  "module": "() => import('@/routes/ieee/author.ts')",
  "name": "IEEE Author Articles",
  "parameters": {
    "aid": "Author ID",
    "sortType": "Sort Type of papers"
  },
  "path": "/author/:aid/:sortType"
}
```
