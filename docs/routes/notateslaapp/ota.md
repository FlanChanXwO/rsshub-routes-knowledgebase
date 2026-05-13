# Not a Tesla App - Tesla Software Updates

## Coverage
`index-only`

## Route
- Namespace: `notateslaapp`
- Namespace Name: `Not a Tesla App`
- Route Path: `/ota`
- Route Name: `Tesla Software Updates`
- Example: `/notateslaapp/ota`
- URL: `notateslaapp.com/software-updates/history`
- Language: `en`
- Categories: `program-update`
- Maintainers: `mrbruce516`
- Source Location: `update.ts`
- Source Module: `() => import('@/routes/notateslaapp/update.ts')`

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
  - `notateslaapp.com/software-updates/history`
  - `notateslaapp.com/software-updates`
  - `notateslaapp.com/`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "example": "/notateslaapp/ota",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "update.ts",
  "maintainers": [
    "mrbruce516"
  ],
  "module": "() => import('@/routes/notateslaapp/update.ts')",
  "name": "Tesla Software Updates",
  "parameters": {},
  "path": "/ota",
  "radar": [
    {
      "source": [
        "notateslaapp.com/software-updates/history",
        "notateslaapp.com/software-updates",
        "notateslaapp.com/"
      ]
    }
  ],
  "url": "notateslaapp.com/software-updates/history"
}
```
