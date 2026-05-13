# The Economist - Espresso

## Coverage
`index-only`

## Route
- Namespace: `economist`
- Namespace Name: `The Economist`
- Route Path: `/espresso`
- Route Name: `Espresso`
- Example: `/economist/espresso`
- URL: `economist.com/the-world-in-brief`
- Language: `en`
- Categories: `traditional-media`
- Maintainers: `TonyRL`
- Source Location: `espresso.ts`
- Source Module: `() => import('@/routes/economist/espresso.ts')`

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
  - `economist.com/the-world-in-brief`
  - `economist.com/espresso`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/economist/espresso",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "espresso.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/economist/espresso.ts')",
  "name": "Espresso",
  "parameters": {},
  "path": "/espresso",
  "radar": [
    {
      "source": [
        "economist.com/the-world-in-brief",
        "economist.com/espresso"
      ]
    }
  ],
  "url": "economist.com/the-world-in-brief",
  "view": 0
}
```
