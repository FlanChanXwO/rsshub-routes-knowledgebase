# The Economist - Category

## Coverage
`index-only`

## Route
- Namespace: `economist`
- Namespace Name: `The Economist`
- Route Path: `/:endpoint`
- Route Name: `Category`
- Example: `/economist/latest`
- URL: `economist.com`
- Language: `en`
- Categories: `traditional-media`
- Maintainers: `ImSingee`
- Source Location: `full.ts`
- Source Module: `() => import('@/routes/economist/full.ts')`

## Description
_None_

## Parameters
- `endpoint`: Category name, can be found on the [official page](https://www.economist.com/rss). For example, https://www.economist.com/china/rss.xml to china


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
  - `economist.com/:endpoint`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/economist/latest",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "full.ts",
  "maintainers": [
    "ImSingee"
  ],
  "module": "() => import('@/routes/economist/full.ts')",
  "name": "Category",
  "parameters": {
    "endpoint": "Category name, can be found on the [official page](https://www.economist.com/rss). For example, https://www.economist.com/china/rss.xml to china"
  },
  "path": "/:endpoint",
  "radar": [
    {
      "source": [
        "economist.com/:endpoint"
      ]
    }
  ],
  "view": 0
}
```
