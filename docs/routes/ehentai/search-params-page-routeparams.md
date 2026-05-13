# E-Hentai - Search

## Coverage
`index-only`

## Route
- Namespace: `ehentai`
- Namespace Name: `E-Hentai`
- Route Path: `/search/:params?/:page?/:routeParams?`
- Route Name: `Search`
- Example: `/ehentai/search/f_cats=1021/0/bittorrent=true&embed_thumb=false`
- URL: `_None_`
- Language: `en`
- Categories: `picture`
- Maintainers: `yindaheng98, syrinka`
- Source Location: `search.ts`
- Source Module: `() => import('@/routes/ehentai/search.ts')`

## Description
_None_

## Parameters
- `params`: Search parameters. You can copy the content after `https://e-hentai.org/?`
- `page`: Page number, set 0 to get latest
- `routeParams`: Additional parameters, see the table above


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: true
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "example": "/ehentai/search/f_cats=1021/0/bittorrent=true&embed_thumb=false",
  "features": {
    "antiCrawler": true,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": true,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "search.ts",
  "maintainers": [
    "yindaheng98",
    "syrinka"
  ],
  "module": "() => import('@/routes/ehentai/search.ts')",
  "name": "Search",
  "parameters": {
    "page": "Page number, set 0 to get latest",
    "params": "Search parameters. You can copy the content after `https://e-hentai.org/?`",
    "routeParams": "Additional parameters, see the table above"
  },
  "path": "/search/:params?/:page?/:routeParams?"
}
```
