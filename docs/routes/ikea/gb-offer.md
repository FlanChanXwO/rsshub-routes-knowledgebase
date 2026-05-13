# IKEA - UK - Offers

## Coverage
`index-only`

## Route
- Namespace: `ikea`
- Namespace Name: `IKEA`
- Route Path: `/gb/offer`
- Route Name: `UK - Offers`
- Example: `/ikea/gb/offer`
- URL: `ikea.com/gb/en/offers`
- Language: `en`
- Categories: `shopping`
- Maintainers: `HenryQW`
- Source Location: `gb/offer.ts`
- Source Module: `() => import('@/routes/ikea/gb/offer.ts')`

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
  - `ikea.com/gb/en/offers`
  - `ikea.com/`

## Raw JSON
```json
{
  "categories": [
    "shopping"
  ],
  "example": "/ikea/gb/offer",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "gb/offer.ts",
  "maintainers": [
    "HenryQW"
  ],
  "module": "() => import('@/routes/ikea/gb/offer.ts')",
  "name": "UK - Offers",
  "parameters": {},
  "path": "/gb/offer",
  "radar": [
    {
      "source": [
        "ikea.com/gb/en/offers",
        "ikea.com/"
      ]
    }
  ],
  "url": "ikea.com/gb/en/offers"
}
```
