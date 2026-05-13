# AppleInsider - Category

## Coverage
`index-only`

## Route
- Namespace: `appleinsider`
- Namespace Name: `AppleInsider`
- Route Path: `/:category?`
- Route Name: `Category`
- Example: `/appleinsider`
- URL: `appleinsider.com`
- Language: `en`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/appleinsider/index.ts')`

## Description
| News | Reviews | How-tos |
| ---- | ------- | ------- |
|      | reviews | how-to  |

## Parameters
- `category`: Category, see below, News by default


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
  - `appleinsider.com/:category`
  - `appleinsider.com/`
- `target`: `/:category`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| News | Reviews | How-tos |\n| ---- | ------- | ------- |\n|      | reviews | how-to  |",
  "example": "/appleinsider",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/appleinsider/index.ts')",
  "name": "Category",
  "parameters": {
    "category": "Category, see below, News by default"
  },
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "appleinsider.com/:category",
        "appleinsider.com/"
      ],
      "target": "/:category"
    }
  ]
}
```
