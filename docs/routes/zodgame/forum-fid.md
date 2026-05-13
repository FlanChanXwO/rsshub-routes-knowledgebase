# ZodGame - forum

## Coverage
`index-only`

## Route
- Namespace: `zodgame`
- Namespace Name: `ZodGame`
- Route Path: `/forum/:fid?`
- Route Name: `forum`
- Example: `/zodgame/forum/13`
- URL: `zodgame.xyz`
- Language: `en`
- Categories: `bbs`
- Maintainers: `FeCCC`
- Source Location: `forum.tsx`
- Source Module: `() => import('@/routes/zodgame/forum.tsx')`

## Description
_None_

## Parameters
- `fid`: forum id, can be found in URL


## Features
- `requireConfig`: [{"description": "", "name": "ZODGAME_COOKIE"}]
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
    "bbs"
  ],
  "example": "/zodgame/forum/13",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": [
      {
        "description": "",
        "name": "ZODGAME_COOKIE"
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "forum.tsx",
  "maintainers": [
    "FeCCC"
  ],
  "module": "() => import('@/routes/zodgame/forum.tsx')",
  "name": "forum",
  "parameters": {
    "fid": "forum id, can be found in URL"
  },
  "path": "/forum/:fid?"
}
```
