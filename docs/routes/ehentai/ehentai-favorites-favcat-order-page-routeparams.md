# E-Hentai - Favorites

## Coverage
`index-only`

## Route
- Namespace: `ehentai`
- Namespace Name: `E-Hentai`
- Route Path: `/ehentai/favorites/:favcat?/:order?/:page?/:routeParams?`
- Route Name: `Favorites`
- Example: `/ehentai/favorites/0/posted/0/bittorrent=true&embed_thumb=false`
- URL: `_None_`
- Language: `_None_`
- Categories: `picture`
- Maintainers: `yindaheng98, syrinka`
- Source Location: `favorites.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `favcat`: Favorites folder number
- `order`: `posted`(Sort by gallery release time) , `favorited`(Sort by time added to favorites)
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
  "example": "/ehentai/favorites/0/posted/0/bittorrent=true&embed_thumb=false",
  "features": {
    "antiCrawler": true,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": true,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "favorites.ts",
  "maintainers": [
    "yindaheng98",
    "syrinka"
  ],
  "name": "Favorites",
  "parameters": {
    "favcat": "Favorites folder number",
    "order": "`posted`(Sort by gallery release time) , `favorited`(Sort by time added to favorites)",
    "page": "Page number, set 0 to get latest",
    "routeParams": "Additional parameters, see the table above"
  },
  "path": "/favorites/:favcat?/:order?/:page?/:routeParams?",
  "topFeeds": []
}
```
