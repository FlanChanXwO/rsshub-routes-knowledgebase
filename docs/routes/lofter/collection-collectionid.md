# Lofter - Collection

## Coverage
`index-only`

## Route
- Namespace: `lofter`
- Namespace Name: `Lofter`
- Route Path: `/collection/:collectionID`
- Route Name: `Collection`
- Example: `/lofter/collection/552041`
- URL: `www.lofter.com`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `SrakhiuMeow`
- Source Location: `collection.ts`
- Source Module: `() => import('@/routes/lofter/collection.ts')`

## Description
_None_

## Parameters
- `collectionID`: Lofter collection ID, can be found in the share URL


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
    "social-media"
  ],
  "example": "/lofter/collection/552041",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "collection.ts",
  "maintainers": [
    "SrakhiuMeow"
  ],
  "module": "() => import('@/routes/lofter/collection.ts')",
  "name": "Collection",
  "parameters": {
    "collectionID": "Lofter collection ID, can be found in the share URL"
  },
  "path": "/collection/:collectionID"
}
```
