# PornHub - Keyword Search

## Coverage
`index-only`

## Route
- Namespace: `pornhub`
- Namespace Name: `PornHub`
- Route Path: `/search/:keyword/:img?`
- Route Name: `Keyword Search`
- Example: `/pornhub/search/stepsister`
- URL: `pornhub.com`
- Language: `en`
- Categories: `multimedia`
- Maintainers: `nczitzk`
- Source Location: `search.ts`
- Source Module: `() => import('@/routes/pornhub/search.ts')`

## Description
_None_

## Parameters
- `keyword`: keyword
- `img`: show images, set to `img=1` to enable


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/pornhub/search/stepsister",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "search.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/pornhub/search.ts')",
  "name": "Keyword Search",
  "parameters": {
    "img": "show images, set to `img=1` to enable",
    "keyword": "keyword"
  },
  "path": "/search/:keyword/:img?",
  "view": 3
}
```
