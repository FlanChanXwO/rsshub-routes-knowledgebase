# NASA - Astronomy Picture of the Day

## Coverage
`index-only`

## Route
- Namespace: `nasa`
- Namespace Name: `NASA`
- Route Path: `/apod`
- Route Name: `Astronomy Picture of the Day`
- Example: `/nasa/apod`
- URL: `apod.nasa.govundefined`
- Language: `en`
- Categories: `picture`
- Maintainers: `nczitzk, williamgateszhao`
- Source Location: `apod.ts`
- Source Module: `() => import('@/routes/nasa/apod.ts')`

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
  - `apod.nasa.govundefined`

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "example": "/nasa/apod",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "apod.ts",
  "maintainers": [
    "nczitzk",
    "williamgateszhao"
  ],
  "module": "() => import('@/routes/nasa/apod.ts')",
  "name": "Astronomy Picture of the Day",
  "parameters": {},
  "path": "/apod",
  "radar": [
    {
      "source": [
        "apod.nasa.govundefined"
      ]
    }
  ],
  "url": "apod.nasa.govundefined",
  "view": 2
}
```
