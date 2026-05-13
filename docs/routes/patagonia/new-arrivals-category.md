# Patagonia - New Arrivals

## Coverage
`index-only`

## Route
- Namespace: `patagonia`
- Namespace Name: `Patagonia`
- Route Path: `/new-arrivals/:category`
- Route Name: `New Arrivals`
- Example: `/patagonia/new-arrivals/mens`
- URL: `patagonia.com`
- Language: `en`
- Categories: `shopping`
- Maintainers: `None`
- Source Location: `new-arrivals.tsx`
- Source Module: `() => import('@/routes/patagonia/new-arrivals.tsx')`

## Description
| Men's | Women's | Kids' & Baby | Packs & Gear |
| ----- | ------- | ------------ | ------------ |
| mens  | womens  | kids         | luggage      |

## Parameters
- `category`: category, see below


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
    "shopping"
  ],
  "description": "| Men's | Women's | Kids' & Baby | Packs & Gear |\n| ----- | ------- | ------------ | ------------ |\n| mens  | womens  | kids         | luggage      |",
  "example": "/patagonia/new-arrivals/mens",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "new-arrivals.tsx",
  "maintainers": [],
  "module": "() => import('@/routes/patagonia/new-arrivals.tsx')",
  "name": "New Arrivals",
  "parameters": {
    "category": "category, see below"
  },
  "path": "/new-arrivals/:category"
}
```
