# Pixabay - Search

## Coverage
`index-only`

## Route
- Namespace: `pixabay`
- Namespace Name: `Pixabay`
- Route Path: `/search/:q/:order?`
- Route Name: `Search`
- Example: `/pixabay/search/cat`
- URL: `pixabay.com`
- Language: `en`
- Categories: `picture`
- Maintainers: `TonyRL`
- Source Location: `search.tsx`
- Source Module: `() => import('@/routes/pixabay/search.tsx')`

## Description
_None_

## Parameters
- `q`: Search term
- `order`: {"default": "latest", "description": "Order", "options": [{"label": "popular", "value": "popular"}, {"label": "latest", "value": "latest"}]}


## Features
- `requireConfig`: [{"description": "", "name": "PIXABAY_KEY", "optional": true}]
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `pixabay.com/:searchType/search/:q`
- `target`: `/search/:q`

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "example": "/pixabay/search/cat",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "",
        "name": "PIXABAY_KEY",
        "optional": true
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "search.tsx",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/pixabay/search.tsx')",
  "name": "Search",
  "parameters": {
    "order": {
      "default": "latest",
      "description": "Order",
      "options": [
        {
          "label": "popular",
          "value": "popular"
        },
        {
          "label": "latest",
          "value": "latest"
        }
      ]
    },
    "q": "Search term"
  },
  "path": "/search/:q/:order?",
  "radar": [
    {
      "source": [
        "pixabay.com/:searchType/search/:q"
      ],
      "target": "/search/:q"
    }
  ],
  "view": 2
}
```
