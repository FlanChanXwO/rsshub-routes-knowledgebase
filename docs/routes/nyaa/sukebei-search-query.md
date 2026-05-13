# Nyaa - Search Result

## Coverage
`index-only`

## Route
- Namespace: `nyaa`
- Namespace Name: `Nyaa`
- Route Path: `/sukebei/search/:query?`
- Route Name: `Search Result`
- Example: `/nyaa/search/psycho-pass`
- URL: `nyaa.si`
- Language: `en`
- Categories: `multimedia`
- Maintainers: `Lava-Swimmer, noname1776, camera-2018`
- Source Location: `main.ts`
- Source Module: `() => import('@/routes/nyaa/main.ts')`

## Description
_None_

## Parameters
- `query`: Search keyword


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: true
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/nyaa/search/psycho-pass",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": true,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "main.ts",
  "maintainers": [
    "Lava-Swimmer",
    "noname1776",
    "camera-2018"
  ],
  "module": "() => import('@/routes/nyaa/main.ts')",
  "name": "Search Result",
  "parameters": {
    "query": "Search keyword"
  },
  "path": [
    "/search/:query?",
    "/user/:username?",
    "/user/:username/search/:query?",
    "/sukebei/search/:query?",
    "/sukebei/user/:username?",
    "/sukebei/user/:username/search/:query?"
  ]
}
```
