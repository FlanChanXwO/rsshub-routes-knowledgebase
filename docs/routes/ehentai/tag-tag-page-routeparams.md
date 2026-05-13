# E-Hentai - Tag

## Coverage
`index-only`

## Route
- Namespace: `ehentai`
- Namespace Name: `E-Hentai`
- Route Path: `/tag/:tag/:page?/:routeParams?`
- Route Name: `Tag`
- Example: `/ehentai/tag/language:chinese/0/bittorrent=true&embed_thumb=false`
- URL: `_None_`
- Language: `en`
- Categories: `picture`
- Maintainers: `yindaheng98, syrinka`
- Source Location: `tag.ts`
- Source Module: `() => import('@/routes/ehentai/tag.ts')`

## Description
_None_

## Parameters
- `tag`: Tag
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
  "example": "/ehentai/tag/language:chinese/0/bittorrent=true&embed_thumb=false",
  "features": {
    "antiCrawler": true,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": true,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "tag.ts",
  "maintainers": [
    "yindaheng98",
    "syrinka"
  ],
  "module": "() => import('@/routes/ehentai/tag.ts')",
  "name": "Tag",
  "parameters": {
    "page": "Page number, set 0 to get latest",
    "routeParams": "Additional parameters, see the table above",
    "tag": "Tag"
  },
  "path": "/tag/:tag/:page?/:routeParams?"
}
```
