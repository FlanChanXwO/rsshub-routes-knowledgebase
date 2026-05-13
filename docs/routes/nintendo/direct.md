# Nintendo - Nintendo Direct

## Coverage
`index-only`

## Route
- Namespace: `nintendo`
- Namespace Name: `Nintendo`
- Route Path: `/direct`
- Route Name: `Nintendo Direct`
- Example: `/nintendo/direct`
- URL: `nintendo.com/nintendo-direct/archive`
- Language: `en`
- Categories: `game`
- Maintainers: `HFO4`
- Source Location: `direct.ts`
- Source Module: `() => import('@/routes/nintendo/direct.ts')`

## Description
_None_

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
  - `nintendo.com/nintendo-direct/archive`
  - `nintendo.com/`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "example": "/nintendo/direct",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "direct.ts",
  "maintainers": [
    "HFO4"
  ],
  "module": "() => import('@/routes/nintendo/direct.ts')",
  "name": "Nintendo Direct",
  "parameters": {},
  "path": "/direct",
  "radar": [
    {
      "source": [
        "nintendo.com/nintendo-direct/archive",
        "nintendo.com/"
      ]
    }
  ],
  "url": "nintendo.com/nintendo-direct/archive"
}
```
