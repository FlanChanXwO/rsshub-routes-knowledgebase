# 報導者 - 分類

## Coverage
`index-only`

## Route
- Namespace: `twreporter`
- Namespace Name: `報導者`
- Route Path: `/category/:category`
- Route Name: `分類`
- Example: `/twreporter/category/world`
- URL: `twreporter.org/`
- Language: `zh-TW`
- Categories: `new-media`
- Maintainers: `emdoe`
- Source Location: `category.ts`
- Source Module: `() => import('@/routes/twreporter/category.ts')`

## Description
_None_

## Parameters
- `category`: Category


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
  - `twreporter.org/:category`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/twreporter/category/world",
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
  "module": "() => import('@/routes/twreporter/category.ts')",
  "name": "分類",
  "parameters": {
    "category": "Category"
  },
  "path": "/category/:category",
  "radar": [
    {
      "source": [
        "twreporter.org/:category"
      ]
    }
  ],
  "url": "twreporter.org/"
}
```
