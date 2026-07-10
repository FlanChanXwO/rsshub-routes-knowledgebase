# Azul - Downloads

## Coverage
`index-only`

## Route
- Namespace: `azul`
- Namespace Name: `Azul`
- Route Path: `/azul/downloads`
- Route Name: `Downloads`
- Example: `/azul/downloads`
- URL: `www.azul.com`
- Language: `_None_`
- Categories: `program-update`
- Maintainers: `nczitzk`
- Source Location: `packages.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.azul.com/downloads`
- `target`: `/downloads`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "example": "/azul/downloads",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 0,
  "location": "packages.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "Downloads",
  "path": "/downloads",
  "radar": [
    {
      "source": [
        "www.azul.com/downloads"
      ],
      "target": "/downloads"
    }
  ],
  "topFeeds": [],
  "url": "www.azul.com",
  "view": 5
}
```
