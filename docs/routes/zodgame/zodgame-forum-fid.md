# ZodGame - forum

## Coverage
`index-only`

## Route
- Namespace: `zodgame`
- Namespace Name: `ZodGame`
- Route Path: `/zodgame/forum/:fid?`
- Route Name: `forum`
- Example: `/zodgame/forum/13`
- URL: `zodgame.xyz`
- Language: `_None_`
- Categories: `bbs`
- Maintainers: `FeCCC`
- Source Location: `forum.tsx`
- Source Module: `_None_`

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
  "heat": 0,
  "location": "forum.tsx",
  "maintainers": [
    "FeCCC"
  ],
  "name": "forum",
  "parameters": {
    "fid": "forum id, can be found in URL"
  },
  "path": "/forum/:fid?",
  "topFeeds": []
}
```
