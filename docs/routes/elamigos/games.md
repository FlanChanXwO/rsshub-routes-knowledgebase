# ElAmigos - Releases

## Coverage
`index-only`

## Route
- Namespace: `elamigos`
- Namespace Name: `ElAmigos`
- Route Path: `/games`
- Route Name: `Releases`
- Example: `/elamigos/games`
- URL: `elamigos.site`
- Language: `en-gb`
- Categories: `game`
- Maintainers: `Kylon92`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/elamigos/index.ts')`

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
  "location": "index.ts",
  "maintainers": [
    "Kylon92"
  ],
  "module": "() => import('@/routes/elamigos/index.ts')",
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
  ]
}
```
