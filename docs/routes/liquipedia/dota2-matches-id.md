# Liquipedia - Dota2 战队最近比赛结果

## Coverage
`index-only`

## Route
- Namespace: `liquipedia`
- Namespace Name: `Liquipedia`
- Route Path: `/dota2/matches/:id`
- Route Name: `Dota2 战队最近比赛结果`
- Example: `/liquipedia/dota2/matches/Team_Aster`
- URL: `liquipedia.net`
- Language: `en`
- Categories: `game`
- Maintainers: `wzekin`
- Source Location: `dota2-matches.ts`
- Source Module: `() => import('@/routes/liquipedia/dota2-matches.ts')`

## Description
_None_

## Parameters
- `id`: 战队名称，可在url中找到。例如:https://liquipedia.net/dota2/Team_Aster


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
  - `liquipedia.net/dota2/:id`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "example": "/liquipedia/dota2/matches/Team_Aster",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "dota2-matches.ts",
  "maintainers": [
    "wzekin"
  ],
  "module": "() => import('@/routes/liquipedia/dota2-matches.ts')",
  "name": "Dota2 战队最近比赛结果",
  "parameters": {
    "id": "战队名称，可在url中找到。例如:https://liquipedia.net/dota2/Team_Aster"
  },
  "path": "/dota2/matches/:id",
  "radar": [
    {
      "source": [
        "liquipedia.net/dota2/:id"
      ]
    }
  ]
}
```
