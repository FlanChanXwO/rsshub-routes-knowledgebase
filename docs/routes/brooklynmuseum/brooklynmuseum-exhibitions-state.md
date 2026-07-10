# Brooklyn Museum - Exhibitions

## Coverage
`index-only`

## Route
- Namespace: `brooklynmuseum`
- Namespace Name: `Brooklyn Museum`
- Route Path: `/brooklynmuseum/exhibitions/:state?`
- Route Name: `Exhibitions`
- Example: `/brooklynmuseum/exhibitions`
- URL: `www.brooklynmuseum.org`
- Language: `_None_`
- Categories: `travel`
- Maintainers: `None`
- Source Location: `exhibitions.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `state`: 展览进行的状态：`current` 对应展览当前正在进行，`past` 对应过去的展览，`upcoming` 对应即将举办的展览，默认为 `current`


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "travel"
  ],
  "example": "/brooklynmuseum/exhibitions",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "exhibitions.ts",
  "maintainers": [],
  "name": "Exhibitions",
  "parameters": {
    "state": "展览进行的状态：`current` 对应展览当前正在进行，`past` 对应过去的展览，`upcoming` 对应即将举办的展览，默认为 `current`"
  },
  "path": "/exhibitions/:state?",
  "topFeeds": []
}
```
