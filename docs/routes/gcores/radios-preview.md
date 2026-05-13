# 机核网 - 预告

## Coverage
`index-only`

## Route
- Namespace: `gcores`
- Namespace Name: `机核网`
- Route Path: `/radios/preview`
- Route Name: `预告`
- Example: `/gcores/radios/preview`
- URL: `www.gcores.com`
- Language: `zh-CN`
- Categories: `game`
- Maintainers: `nczitzk`
- Source Location: `program-previews.ts`
- Source Module: `() => import('@/routes/gcores/program-previews.ts')`

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
  - `www.gcores.com/radios/preview`
- `target`: `/gcores/radios/preview`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "example": "/gcores/radios/preview",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "program-previews.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/gcores/program-previews.ts')",
  "name": "预告",
  "path": "/radios/preview",
  "radar": [
    {
      "source": [
        "www.gcores.com/radios/preview"
      ],
      "target": "/gcores/radios/preview"
    }
  ],
  "url": "www.gcores.com",
  "view": 5
}
```
