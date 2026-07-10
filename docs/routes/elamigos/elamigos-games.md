# ElAmigos - Releases

## Coverage
`index-only`

## Route
- Namespace: `elamigos`
- Namespace Name: `ElAmigos`
- Route Path: `/elamigos/games`
- Route Name: `Releases`
- Example: `/elamigos/games`
- URL: `elamigos.site`
- Language: `_None_`
- Categories: `game`
- Maintainers: `Kylon92`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
Latest game releases from ElAmigos

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `elamigos.site/`
  - `elamigos.site/index.html`
- `target`: `/games`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "Latest game releases from ElAmigos",
  "example": "/elamigos/games",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "index.ts",
  "maintainers": [
    "Kylon92"
  ],
  "name": "Releases",
  "parameters": {},
  "path": "/games",
  "radar": [
    {
      "source": [
        "elamigos.site/",
        "elamigos.site/index.html"
      ],
      "target": "/games"
    }
  ],
  "topFeeds": []
}
```
