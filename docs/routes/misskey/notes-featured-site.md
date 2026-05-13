# Misskey - Featured Notes

## Coverage
`index-only`

## Route
- Namespace: `misskey`
- Namespace Name: `Misskey`
- Route Path: `/notes/featured/:site`
- Route Name: `Featured Notes`
- Example: `/misskey/notes/featured/misskey.io`
- URL: `misskey.io`
- Language: `en`
- Categories: `social-media`
- Maintainers: `Misaka13514`
- Source Location: `featured-notes.ts`
- Source Module: `() => import('@/routes/misskey/featured-notes.ts')`

## Description
_None_

## Parameters
- `site`: instance address, domain only, without `http://` or `https://` protocol header


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
  "example": "/misskey/notes/featured/misskey.io",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "featured-notes.ts",
  "maintainers": [
    "Misaka13514"
  ],
  "module": "() => import('@/routes/misskey/featured-notes.ts')",
  "name": "Featured Notes",
  "parameters": {
    "site": "instance address, domain only, without `http://` or `https://` protocol header"
  },
  "path": "/notes/featured/:site",
  "view": 1
}
```
