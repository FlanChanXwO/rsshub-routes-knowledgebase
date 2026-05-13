# CSS-Tricks - CSS Guides

## Coverage
`index-only`

## Route
- Namespace: `css-tricks`
- Namespace Name: `CSS-Tricks`
- Route Path: `/collections/:type`
- Route Name: `CSS Guides`
- Example: `/css-tricks/collections/2`
- URL: `css-tricks.com`
- Language: `en`
- Categories: `programming`
- Maintainers: `Rjnishant530`
- Source Location: `collections.ts`
- Source Module: `() => import('@/routes/css-tricks/collections.ts')`

## Description
_None_

## Parameters
- `category`: {"description": "Collection Type", "options": [{"label": "Latest CSS Guides", "value": "3"}, {"label": "Fresh From the Almanac", "value": "2"}, {"label": "Classic Tricks", "value": "4"}]}


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
  - `css-tricks.com`
- `target`: `/collections/:type`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/css-tricks/collections/2",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "collections.ts",
  "maintainers": [
    "Rjnishant530"
  ],
  "module": "() => import('@/routes/css-tricks/collections.ts')",
  "name": "CSS Guides",
  "parameters": {
    "category": {
      "description": "Collection Type",
      "options": [
        {
          "label": "Latest CSS Guides",
          "value": "3"
        },
        {
          "label": "Fresh From the Almanac",
          "value": "2"
        },
        {
          "label": "Classic Tricks",
          "value": "4"
        }
      ]
    }
  },
  "path": "/collections/:type",
  "radar": [
    {
      "source": [
        "css-tricks.com"
      ],
      "target": "/collections/:type"
    }
  ],
  "view": 0
}
```
