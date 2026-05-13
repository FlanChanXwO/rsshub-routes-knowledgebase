# AEON - Categories

## Coverage
`index-only`

## Route
- Namespace: `aeon`
- Namespace Name: `AEON`
- Route Path: `/category/:category`
- Route Name: `Categories`
- Example: `/aeon/category/philosophy`
- URL: `aeon.co`
- Language: `en`
- Categories: `new-media`
- Maintainers: `emdoe`
- Source Location: `category.ts`
- Source Module: `() => import('@/routes/aeon/category.ts')`

## Description
_None_

## Parameters
- `category`: {"description": "Category", "options": [{"label": "Philosophy", "value": "philosophy"}, {"label": "Science", "value": "science"}, {"label": "Psychology", "value": "psychology"}, {"label": "Society", "value": "society"}, {"label": "Culture", "value": "culture"}]}


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
  - `aeon.co/:category`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/aeon/category/philosophy",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "category.ts",
  "maintainers": [
    "emdoe"
  ],
  "module": "() => import('@/routes/aeon/category.ts')",
  "name": "Categories",
  "parameters": {
    "category": {
      "description": "Category",
      "options": [
        {
          "label": "Philosophy",
          "value": "philosophy"
        },
        {
          "label": "Science",
          "value": "science"
        },
        {
          "label": "Psychology",
          "value": "psychology"
        },
        {
          "label": "Society",
          "value": "society"
        },
        {
          "label": "Culture",
          "value": "culture"
        }
      ]
    }
  },
  "path": "/category/:category",
  "radar": [
    {
      "source": [
        "aeon.co/:category"
      ]
    }
  ]
}
```
